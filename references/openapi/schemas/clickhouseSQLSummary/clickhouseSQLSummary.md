# clickhouseSQLSummary

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `queryCount` | integer (int64) | No | Finished and failed queries in the selected range. |
| `failedCount` | integer (int64) | No | Queries that ended with ExceptionWhileProcessing. |
| `slowQueryCount` | integer (int64) | No | Queries whose duration is at least 1000 ms. |
| `totalDurationMs` | number (double) | No | Sum of query_duration_ms for all finished and failed queries. |

