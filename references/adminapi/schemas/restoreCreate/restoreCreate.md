# restoreCreate

RestoreCreate is the payload to restore a KubeBlocks cluster

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `environmentName` | string | Yes | the env name of the target environment to restore |
| `backupId` | string | Yes | the id of backup to restore |
| `cluster` | [clusterCreate](clusterCreate.md) | Yes |  |
| `restoreTimeStr` | string | No | Target time for point-in-time recovery, only supported with a Continuous backup ID. Use an RFC3339 timestamp at whole-second precision, for example 2026-10-22T08:30:00Z or 2026-10-22T16:30:00+08:00. Timezone offsets are converted to UTC without changing the instant. Non-zero fractional seconds and UTC years outside 0000-9999 are rejected. Omit or leave empty to retain the backup method's default restore behavior. |
| `doReadyRestoreAfterClusterRunning` | boolean | No | the recovery process in the PostReady phase will be performed after the cluster is running successfully. |
| `volumeRestorePolicy` | [volumeRestorePolicy](volumeRestorePolicy.md) | No |  |

