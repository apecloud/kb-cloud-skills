# clickhouseFailedQuery

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `eventTime` | string | No | query_log event time in RFC3339 UTC. |
| `queryId` | string | No | ClickHouse query_id. |
| `user` | string | No | User that ran the query. |
| `database` | string | No | Current database at execution time. |
| `query` | string | No | Query text with string and numeric literals and comments masked as ?. |
| `exceptionCode` | integer (int64) | No | ClickHouse exception code. |
| `exceptionCategory` | string | No | Best-effort category such as memory_limit_exceeded, timeout, too_many_parts, readonly, unknown_table or syntax_error. |
| `exception` | string | No | Full exception text. |
| `durationMs` | number (double) | No | query_duration_ms before the failure. |
| `memoryUsageBytes` | integer (int64) | No | Memory usage in bytes. |
| `hostName` | string | No | ClickHouse server host that ran the query. |

