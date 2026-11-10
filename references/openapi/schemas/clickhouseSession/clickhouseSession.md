# clickhouseSession

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `queryId` | string | Yes | ClickHouse query_id. Use it with the KILL QUERY endpoint. |
| `initialQueryId` | string | No | query_id of the initial (distributed) query when this row is a remote sub-query. |
| `user` | string | No | User that started the query. |
| `address` | string | No | Client address. |
| `port` | integer (int64) | No | Client port. |
| `database` | string | No | Current database of the query. |
| `hostName` | string | No | ClickHouse server host that reported the query. |
| `elapsedSeconds` | number (double) | No | Seconds elapsed since the query started. |
| `readRows` | integer (int64) | No | Rows read so far. |
| `readBytes` | integer (int64) | No | Bytes read so far. |
| `writtenRows` | integer (int64) | No | Rows written so far. |
| `writtenBytes` | integer (int64) | No | Bytes written so far. |
| `memoryUsageBytes` | integer (int64) | No | Current memory usage in bytes. |
| `memoryLimitBytes` | integer (int64) | No | max_memory_usage from the query Settings map (only explicitly modified settings). Zero means the query did not set a limit, so the server default applies. |
| `memoryUsageRatio` | number (double) | No | memory_usage / memoryLimitBytes (0-1). Zero when the query did not explicitly set max_memory_usage. Values close to 1 indicate the query is about to hit its memory limit. |
| `peakMemoryUsageBytes` | integer (int64) | No | Peak memory usage in bytes. Zero when the server version does not expose peak_memory_usage. |
| `isInitialQuery` | boolean | No | Whether this row is the initial query rather than a remote sub-query. |
| `queryStartTime` | string | No | Estimated query start time in RFC3339 UTC, computed from elapsed because system.processes has no start timestamp. |
| `query` | string | No | Query text with string and numeric literals and comments masked as ? before returning. |
| `querySummary` | string | No | Single-line masked query summary suitable for list rendering. |

