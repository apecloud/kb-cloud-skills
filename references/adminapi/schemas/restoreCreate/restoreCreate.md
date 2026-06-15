# restoreCreate

RestoreCreate is the payload to restore a KubeBlocks cluster

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `environmentName` | string | Yes | the env name of the target environment to restore |
| `backupId` | string | Yes | the id of backup to restore |
| `cluster` | [clusterCreate](clusterCreate.md) | Yes |  |
| `restoreTimeStr` | string | No | restoreTime point to restore |
| `doReadyRestoreAfterClusterRunning` | boolean | No | the recovery process in the PostReady phase will be performed after the cluster is running successfully. |
| `volumeRestorePolicy` | [volumeRestorePolicy](volumeRestorePolicy.md) | No |  |

