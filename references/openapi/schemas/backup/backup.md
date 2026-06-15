# backup

backup is the payload for KubeBlocks cluster backup

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `autoBackup` | boolean | Yes | autoBackup or not |
| `backupMethod` | string | Yes | Backup Method. |
| `backupPolicyName` | string | Yes | Which backupPolicy is applied to perform this backup |
| `backupRepo` | string | No | backupRepo is the name of backupRepo and it is used to store the backup data |
| `backupType` | [backupType](backupType.md) | Yes |  |
| `completionTimestamp` | string (date-time) | No | Date/time when the backup finished being processed. |
| `creationTimestamp` | string (date-time) | Yes | Date/time when the backup was created. |
| `duration` | string | No | The duration time of backup execution. When converted to a string, the form is "1h2m0.5s". |
| `name` | string | Yes | name of the backup |
| `orgName` | string | Yes | orgName records the organization name for this backup. |
| `snapshotVolumes` | boolean | Yes | snapshotVolumes specifies whether to take snapshots of persistent volumes to back up |
| `sourceCluster` | string | Yes | sourceCluster records the source cluster information for this backup. |
| `startTimestamp` | string (date-time) | No | Date/time when the backup started being processed. |
| `status` | [backupStatus](backupStatus.md) | Yes |  |
| `timeRangeEnd` | string (date-time) | No | timeRangeEnd records the end time of the backup. |
| `timeRangeStart` | string (date-time) | No | timeRangeStart records the start time of the backup. |
| `totalSize` | string | Yes | Backup total size. A string with capacity units in the form of "1Gi", "1Mi", "1Ki". |
| `failureReason` | string | No |  |
| `extras` | string | No |  |
| `parameters` | object[] | No | backup parameters |
| `selectedObjects` | selectiveObjectTreeNode[] | No | backup selected objects |
| `targetPods` | string[] | No | backup target pods |
| `path` | string | No | the path of backup files |
| `retentionPeriod` | string | Yes | determines a duration up to which the backup should be kept |
| `expiration` | string (date-time) | No | indicates when this backup becomes eligible for garbage collection |
| `id` | string | No | the backup id |
| `clusterId` | string | No | the id of cluster that backup belong to |
| `cloudProvider` | string | No | the cloud provider |
| `cloudRegion` | string | No | the cloud region |
| `environmentName` | string | Yes | the environment name |
| `engine` | string | Yes | the cluster engine |
| `parentBackupName` | string | No | the parent backup name |
| `baseBackupName` | string | No | the base backup name |
| `encryptionKeyName` | string | No | the key name used for encryption |

## Nested Fields

### `parameters`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | the name of parameter |
| `value` | string | No | the value of parameter |

