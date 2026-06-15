# backupScheduleCreate

payload to create a backup schedule

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `scheduleName` | string | Yes | the name of backup schedule |
| `backupMethod` | string | Yes | the backup method |
| `parameters` | object | No | backup parameters |
| `selectedObjects` | selectiveObjectTreeNode[] | No | backup selected objects |
| `cronExpression` | string | No | the cron expression for backup schedule |

