# Storage

## S3

### S3 Object Lock

Allows objects to be stored using the *WORM* model (write one, read many).  Prevents objects or across the bucket from being deleted or modified, under the following conditions:

- For a defined period of time, called *Retention Period*.
- Locked indefinitely.
- Until the condition , called *Legal Hold*, is removed.  Users who want to place or remove the condition on objects must have the `s3:PutObjectLegalHold` permission.


#### Governance Mode

It is the mode where only authorized users can delete the object or modify its lock settings.

#### Compliance Mode

It is the mode in wich not even the root user can modify or delete the objects, and they are only released when their retention period ends.

### Glacier Vault Lock

Allows you to deploy and enforce compliance controls for individual s3 Glacier vaults storage (*legacy*) with a vault policy: *WORM* can be used.  Once locked, the policy can no longer be changed.
