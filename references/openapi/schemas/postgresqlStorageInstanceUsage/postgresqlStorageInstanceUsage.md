# postgresqlStorageInstanceUsage

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `instanceName` | string | No | Kubernetes pod name for this PostgreSQL replica storage sample. |
| `pvcName` | string | No | PersistentVolumeClaim name when it can be read from metrics labels. |
| `role` | string | No | Raw PostgreSQL replica role value read from metrics labels, kept aligned with instance detail display. |
| `componentName` | string | No | Optional KubeBlocks component name when it can be read from metrics labels. |
| `totalBytes` | integer (int64) | No | Physical PVC capacity in bytes for this replica storage sample. |
| `usedBytes` | integer (int64) | No | Physical PVC used bytes for this replica storage sample. |
| `availableBytes` | integer (int64) | No | Available bytes derived from totalBytes - usedBytes when both values are available. |
| `usageRatio` | number (double) | No | usedBytes / totalBytes for this replica storage sample when both values are available. |
| `updatedAt` | string | No | Metrics collection timestamp in UTC. |
| `source` | string | No |  |

