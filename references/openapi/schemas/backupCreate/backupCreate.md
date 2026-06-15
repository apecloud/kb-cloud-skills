# backupCreate

BackupCreate is the payload to create a KubeBlocks cluster backup

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | name of the backup, if not specified, a name will be generated automatically |
| `backupType` | [backupType](backupType.md) | No |  |
| `backupMethod` | string | Yes | specified the backup method |
| `component` | string | No | component of the cluster to back up |
| `retentionPeriod` | string | No | specify the retention period |
| `parameters` | any | No | parameters for the backup |
| `selectedObjects` | selectiveObjectTreeNode[] | No | selected objects for the backup |

