# clusterLogHitsItem

A single time bucket in the log hits histogram

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `timestamp` | integer (int64) | No |  |
| `count` | integer (int64) | No |  |
| `avgExecutionTime` | number (double) | No | Average slow log execution time in seconds for this time bucket. Only returned for slow logs. |

