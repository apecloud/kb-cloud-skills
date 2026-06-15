# backupMethodOption

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes |  |
| `compatibleMethod` | string | No | The compatible full backup method for incremental backup method |
| `realBackupPath` | string | No | The actual path where the backup data is stored. If not set, use the backup.status.path. |
| `restoreOption` | object | No |  |
| `notSupportedModes` | string[] | No | The cluster modes that this backup method does not support |
| `description` | [localizedDescription](localizedDescription.md) | No |  |

## Nested Fields

### `restoreOption`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `restoreOnComponents` | string[] | No | If this backup needs to be restored on multiple components, the names of those components must be specified.
If the restore is only required on the backed-up component itself, then no configuration is needed.
 |
| `deferPostReadyUntilClusterRunning` | boolean | No | If set to true, the restore will be ready after the cluster is running.
If set to false, the restore will be ready after the cluster is created.
 |

