# clusterSlowLogTemplate

Aggregated slow log query template

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `templateId` | string | No | Query template identifier |
| `normalizedQuery` | string | No | Normalized SQL or command template |
| `sampleSQL` | string | No | Representative SQL sample for the template |
| `totalCount` | integer (int64) | No |  |
| `totalExecutionTime` | number (double) | No | Total execution time in seconds |
| `avgExecutionTime` | number (double) | No | Average execution time in seconds |
| `minExecutionTime` | number (double) | No | Minimum execution time in seconds |
| `maxExecutionTime` | number (double) | No | Maximum execution time in seconds |
| `stddevExecutionTime` | number (double) | No | Standard deviation of execution time in seconds |
| `p50ExecutionTime` | number (double) | No | P50 execution time in seconds |
| `p90ExecutionTime` | number (double) | No | P90 execution time in seconds |
| `p95ExecutionTime` | number (double) | No | P95 execution time in seconds |
| `p99ExecutionTime` | number (double) | No | P99 execution time in seconds |
| `dbCount` | integer (int64) | No | Number of unique database names in the time range |
| `userCount` | integer (int64) | No | Number of unique users in the time range |
| `clientIPCount` | integer (int64) | No | Number of unique client IPs in the time range |
| `appCount` | integer (int64) | No | Number of unique application names in the time range |
| `avgRowsExamined` | number (double) | No | Average rows examined by the template |
| `avgRowsSent` | number (double) | No | Average rows returned or sent by the template |
| `avgLockTime` | number (double) | No | Average lock wait time in seconds |
| `dbNames` | string[] | No | Sampled database names for the template |
| `users` | string[] | No | Sampled users for the template |
| `clientIPs` | string[] | No | Sampled client IPs for the template |
| `apps` | string[] | No | Sampled application names for the template |

