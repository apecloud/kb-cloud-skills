# clusterSlowLogStats

Summary statistics for slow logs

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `totalSlowLogs` | integer (int64) | No |  |
| `avgExecutionTime` | number (double) | No |  |
| `p95Latency` | number (double) | No |  |
| `activeDBs` | integer (int64) | No |  |
| `databaseDistribution` | clusterSlowLogDatabaseDistribution[] | No | Slow log count distribution grouped by database. Null means the engine does not expose a stable database field. |

