# backupRepoCreate

BackupRepoCreate is the payload to create a KubeBlocks cluster backup repo

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `storageID` | string | Yes | the id of storage that backup repo used |
| `accessMethod` | [backupRepoAccessMethod](backupRepoAccessMethod.md) | No |  |
| `default` | boolean | No | default specifies whether the backupRepo is the default backupRepo |
| `name` | string | Yes | name of the backupRepo |
| `params` | object | No | the parameters to create the storage |
| `pvReclaimPolicy` | [backupRepoPVReclaimPolicy](backupRepoPVReclaimPolicy.md) | No |  |
| `volumeCapacity` | string | No | Specify the capacity of the new created PVC |

