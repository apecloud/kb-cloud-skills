# backupSchedule

backup schedule for database table backup

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | the backup schedule id |
| `scheduleName` | string | No | the name of backup schedule |
| `clusterId` | string | No | the cluster id |
| `backupMethod` | string | No | the backup method |
| `parameters` | object[] | No | backup parameters |
| `selectedObjects` | selectiveObjectTreeNode[] | No | backup selected objects |
| `createdAt` | string (date-time) | No | the creation time |
| `updatedAt` | string (date-time) | No | the last update time |
| `cronExpression` | string | No | the cron expression for backup schedule |

## Nested Fields

### `parameters`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | the name of parameter |
| `value` | string | No | the value of parameter |

