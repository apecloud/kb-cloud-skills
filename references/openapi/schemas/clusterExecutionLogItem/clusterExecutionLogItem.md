# clusterExecutionLogItem

Cluster execution log item represents a single log entry

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `client` | string | No |  |
| `command` | string | No |  |
| `dbName` | string | No |  |
| `executionTime` | number (double) | No |  |
| `slowLog` | [clusterSlowLogDetail](clusterSlowLogDetail.md) | No |  |
| `extra` | object | No |  |
| `timestamp` | integer (int64) | No |  |
| `user` | string | No |  |

