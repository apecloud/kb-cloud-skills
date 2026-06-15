# environmentModuleLogs

Environment module pod logs

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `environmentId` | string | No | Environment ID |
| `moduleName` | string | No | Environment module name |
| `podName` | string | No | Pod name |
| `containerName` | string | No | Container name |
| `logs` | logEntry[] | No |  |
| `nextTimestamp` | string (date-time) | No | Next timestamp for pagination |

