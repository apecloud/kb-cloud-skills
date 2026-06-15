# clusterBackup

clusterBackup is the payload for cluster backup

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `pitrEnabled` | boolean | No | PITREnabled or not |
| `continuousBackupMethod` | string | No | continuous backup method for pitr |
| `autoBackup` | boolean | No | autoBackup or not |
| `autoBackupMethod` | string | No | name of the backup method |
| `backupRepo` | string | No | backupRepoName is the name of backupRepo and it is used to store the backup data |
| `cronExpression` | string | No | cronExpression specifies the cron expression |
| `retentionPeriod` | string | No | retentionPeriod specifies the retention period |
| `retentionPolicy` | [backupRetentionPolicy](backupRetentionPolicy.md) | No |  |
| `snapshotVolumes` | boolean | No | snapshotVolumes specifies whether to take snapshots of persistent volumes to back up |
| `incrementalBackupEnabled` | boolean | No | specify whether to enable incremental backup |
| `incrementalCronExpression` | string | No | the crop expression for incremental backup schedule |

