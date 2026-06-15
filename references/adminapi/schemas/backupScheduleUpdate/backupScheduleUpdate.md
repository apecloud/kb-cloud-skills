# backupScheduleUpdate

payload to update a backup schedule

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `scheduleName` | string | No | the name of backup schedule |
| `backupMethod` | string | No | the backup method |
| `parameters` | object | No | backup parameters |
| `selectedObjects` | selectiveObjectTreeNode[] | No | backup selected objects |
| `cronExpression` | string | No | the cron expression for backup schedule |

