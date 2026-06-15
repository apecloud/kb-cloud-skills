# instanceStorageItem

Instance storage information

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | Specify the name of storage, which must be unique. |
| `size` | string | Yes | Specify the size of storage, the unit is Gi. |
| `storageClass` | string | No | The name of StorageClass in use |
| `ioReserves` | [ioQuantity](ioQuantity.md) | No |  |
| `ioLimits` | [ioQuantity](ioQuantity.md) | No |  |

