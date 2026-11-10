# clickhouseQueryPattern

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `normalizedQueryHash` | string | No | normalized_query_hash as a string. |
| `sampleQuery` | string | No | One representative query text for the pattern, with string and numeric literals and comments masked as ?. |
| `calls` | integer (int64) | No | Number of executions of the pattern. |
| `totalDurationMs` | number (double) | No | Sum of query_duration_ms across all executions. |
| `meanDurationMs` | number (double) | No | Average query_duration_ms. |
| `maxDurationMs` | number (double) | No | Maximum query_duration_ms. |
| `readRows` | integer (int64) | No | Sum of read_rows. |
| `memoryUsageBytes` | integer (int64) | No | Sum of memory_usage in bytes. |
| `failureCount` | integer (int64) | No | Executions that ended with ExceptionWhileProcessing. |
| `slowCallCount` | integer (int64) | No | Executions whose duration is at least 1000 ms. |
| `firstSeen` | string | No | First event_time in RFC3339 UTC. |
| `lastSeen` | string | No | Last event_time in RFC3339 UTC. |

