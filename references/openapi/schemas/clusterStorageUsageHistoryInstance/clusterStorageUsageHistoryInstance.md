# clusterStorageUsageHistoryInstance

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `instanceName` | string | No | Kubernetes pod name for this storage usage series. |
| `pvcName` | string | No | PersistentVolumeClaim name when it can be read from metrics labels. |
| `role` | string | No | Raw database replica role value read from metrics labels, kept aligned with instance detail display. |
| `componentName` | string | No | Optional KubeBlocks component name when it can be read from metrics labels. |
| `points` | clusterStorageUsageHistoryPoint[] | Yes |  |
| `source` | string | No |  |

