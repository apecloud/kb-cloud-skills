# backupPolicy

BackupPolicy is the payload for KubeBlocks cluster backup policy

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `autoBackup` | boolean | No | specify whether to use auto backup |
| `autoBackupMethod` | string | No | the auto full backup method |
| `pitrEnabled` | boolean | No | specify whether to enable point-in-time recovery |
| `continuousBackupMethod` | string | No | continuous backup method for pitr |
| `cronExpression` | string | No | the crop expression for schedule |
| `incrementalBackupEnabled` | boolean | No | specify whether to enable incremental backup |
| `incrementalCronExpression` | string | No | the crop expression for incremental backup schedule |
| `retentionPeriod` | string | No | specify the retention period |
| `backupRepo` | string | No | the backup repo name, which is used to store backup data |
| `retentionPolicy` | [backupRetentionPolicy](backupRetentionPolicy.md) | No |  |
| `nextBackupTime` | string (date-time) | No | the time to do next backup |
| `encryptionConfig` | [encryptionConfig](encryptionConfig.md) | No |  |
| `backupParameters` | object | No |  |

