# backupStats

Backup statistic info

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `backupStatsStatus` | backupStatsStatus[] | No | Number of backups for each different status |
| `backupStatsEngine` | backupStatsEngine[] | No | TotalSize and number of backups for each engine |
| `backupStatsType` | backupStatsType[] | No | TotalSize and number of backups for each type |
| `latestBackupTime` | string (date-time) | No | create time of the latest backup |
| `latestBackupStatus` | string | No | backup status of the latest backup |

