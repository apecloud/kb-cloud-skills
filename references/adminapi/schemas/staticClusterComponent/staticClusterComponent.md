# staticClusterComponent

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `component` | string | Yes | Exact component name supported by the selected engine during environment installation. Each component may appear only once. |
| `replicas` | integer (int64) | No | Number of replicas. Omit to keep the installer default. |
| `classCode` | string | No | Resource class for this exact engine, mode and component. Omit to keep the installer default. |
| `storage` | number (double) | No | Disk capacity in Gi. Only vm-storage, vlstorage and minio accept this field. |

