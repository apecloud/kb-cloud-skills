# environmentStorage

Storage config

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | the storage name |
| `type` | [environmentStorageType](environmentStorageType.md) | No |  |
| `reusedClusterName` | string | No | the existed cluster name for creating storage |
| `reusedClusterNamespace` | string | No | the existed cluster namespace for creating storage |
| `config` | [storageCreate](storageCreate.md) | No |  |
| `cluster` | [staticCluster](staticCluster.md) | No |  |

