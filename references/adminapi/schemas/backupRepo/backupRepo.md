# backupRepo

backupRepo is the payload for KubeBlocks cluster backup repo

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `accessMethod` | [backupRepoAccessMethod](backupRepoAccessMethod.md) | No |  |
| `id` | string | No | the id of backup repo |
| `backupNums` | integer | No | backupNums specifies the number of backups in the backupRepo |
| `config` | object | Yes | config specifies the configuration of the backupRepo |
| `createdAt` | string (date-time) | Yes | createdAt specifies the creation time of the backupRepo |
| `default` | boolean | Yes | default specifies whether the backupRepo is the default backupRepo |
| `environmentId` | string (uuid) | Yes | environmentId of the backupRepo |
| `environmentName` | string | Yes | environmentName of the backupRepo |
| `name` | string | Yes | name of the backupRepo |
| `status` | string | No | status specifies the status of the backupRepo |
| `storageName` | string | No | the name of storage used by backup repo |
| `storageID` | string | No | the id of storage used by backup repo |
| `storageProvider` | string | Yes | storageProvider specifies the storage provider of the backupRepo |
| `totalSize` | string | No | totalSize specifies the total size of backups in the backupRepo |
| `failedReason` | string | No | failedReason specifies the reason of the backupRepo failure |
| `failedMessage` | string | No | failedMessage specifies the message of the backupRepo failure |

