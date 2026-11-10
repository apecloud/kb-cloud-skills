# clickhouseSlowQuery

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `queryId` | string | No | ClickHouse query_id. |
| `initialQueryId` | string | No | Initial query_id for a distributed query. |
| `type` | string | No | query_log type (QueryFinish or ExceptionWhileProcessing). |
| `user` | string | No | User that ran the query. |
| `database` | string | No | Current database at execution time. |
| `queryKind` | string | No | Query kind reported by ClickHouse. |
| `query` | string | No | Query text with string and numeric literals and comments masked as ?. |
| `normalizedQueryHash` | string | No | normalized_query_hash as a string to avoid precision loss in clients. |
| `durationMs` | number (double) | No | query_duration_ms. |
| `readRows` | integer (int64) | No | Rows read by the query. |
| `readBytes` | integer (int64) | No | Bytes read by the query. |
| `memoryUsageBytes` | integer (int64) | No | Memory usage in bytes. |
| `resultRows` | integer (int64) | No | Rows returned by the query. |
| `resultBytes` | integer (int64) | No | Bytes returned by the query. |
| `exceptionCode` | integer (int64) | No | ClickHouse exception code, zero for successful queries. |
| `exception` | string | No | Exception text for failed queries. |
| `eventTime` | string | No | query_log event time in RFC3339 UTC. |
| `hostName` | string | No | ClickHouse server host that ran the query. |
| `clientName` | string | No | Client name reported by ClickHouse. |
| `isInitialQuery` | boolean | No | Whether this is the initial query rather than a remote sub-query. |

