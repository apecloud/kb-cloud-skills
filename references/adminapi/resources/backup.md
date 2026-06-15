# backup

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/backups` | Create backup | [View](../operations/createClusterBackup.md) |
| POST | `/admin/v1/environments/{environmentName}/organizations/{orgName}/engines/{engineName}/buildBackup` | build backup object with a existing backup directory | [View](../operations/buildBackupObj.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/backupPolicy` | Get backup policy | [View](../operations/getClusterBackupPolicy.md) |
| PATCH | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/backupPolicy` | Update backup policy | [View](../operations/updateBackupPolicy.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/listObjectsForSelectiveBackup` | List objects tree for selective backup | [View](../operations/listObjectsTreeForSelectiveBackup.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/backupSchedules` | List backup schedules | [View](../operations/listBackupSchedules.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/backupSchedules` | Create backup schedule | [View](../operations/createBackupSchedule.md) |
| DELETE | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/backupSchedules/{scheduleName}` | Delete backup schedule | [View](../operations/deleteBackupSchedule.md) |
| PATCH | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/backupSchedules/{scheduleName}` | Update backup schedule | [View](../operations/updateBackupSchedule.md) |
| GET | `/admin/v1/backups` | List backups | [View](../operations/listBackups.md) |
| GET | `/admin/v1/backupStats` | Get backup statistics | [View](../operations/getBackupStats.md) |
| GET | `/admin/v1/organizations/{orgName}/backups/{backupId}` | Get backup | [View](../operations/getBackup.md) |
| DELETE | `/admin/v1/organizations/{orgName}/backups/{backupId}` | Delete backup | [View](../operations/deleteBackup.md) |
| GET | `/admin/v1/organizations/{orgName}/backups/{backupId}/logs` | Get backup log | [View](../operations/getBackupLog.md) |
| POST | `/admin/v1/organizations/{orgName}/backups/{backupId}/view` | view backup info | [View](../operations/viewBackup.md) |
| GET | `/admin/v1/organizations/{orgName}/backups/{backupId}/download` | Download full backup | [View](../operations/downloadBackup.md) |
| POST | `/admin/v1/organizations/{orgName}/backups/{backupId}/download` | Download multiple backup files | [View](../operations/downloadMultipleBackups.md) |
