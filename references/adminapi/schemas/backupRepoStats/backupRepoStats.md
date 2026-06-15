# backupRepoStats

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `totalBackup` | integer (int64) | No | the total backup in backup repo |
| `totalSize` | string | No | the total backup size in backup repo |
| `backupStatsStatus` | backupStatsStatus[] | No | Number of backups for each defferent status |
| `backupStatsEngine` | backupStatsEngine[] | No | Totalsize and number of backups for each engine |
| `backupStatsType` | backupStatsType[] | No | Totalsize and number of backups for each engine |
| `createdAt` | string (date-time) | No | the time that the stats is created |

