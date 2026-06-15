# opsIoQuotas

IO Quotas describes IOPS and BPS for volumes of a KubeBlocks cluster

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `component` | string | Yes |  |
| `volumes` | object[] | Yes |  |

## Nested Fields

### `volumes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | volume name |
| `ioReserves` | [ioQuantity](ioQuantity.md) | No |  |
| `ioLimits` | [ioQuantity](ioQuantity.md) | No |  |

