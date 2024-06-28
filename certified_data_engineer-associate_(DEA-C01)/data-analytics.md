# AWS Streaming Data

## Non-monotonic Operations

- [ ] Tumbling Windows (Aggregations Using ```GROUP BY```): each of the resulting windows processed by a query in a non-overlapping manner. In this case, each record on an in-application stream belongs to a specific window. It is processed only once (when the query processes the window to which the record belongs).  ⚡Its recommended to do the exercises⚡ --> [Tumbling Windows](https://docs.aws.amazon.com/kinesisanalytics/latest/dev/tumbling-window-concepts.html)
- [ ] Sliding Windows
- [ ] Session Windows

## Unbounded Queries

- [ ] Session Windows

## Order of Events

- [ ] Event Time
- [ ] Processing Time

- [ ] Apache Flink Watermarks
- [ ] Perfect Watermarks
- [ ] Heuristic Watermarks and Allowed Lateness
