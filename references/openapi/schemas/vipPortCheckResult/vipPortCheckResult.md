# vipPortCheckResult

VIP port check result

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `conflicts` | integer[] | No | Requested ports that are already in use |
| `ip` | string | Yes | Checked VIP address |
| `occupiedPorts` | object[] | Yes | Ports already used on the VIP. Resource ownership details are intentionally omitted. |

## Nested Fields

### `occupiedPorts`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `port` | integer (int32) | Yes | Port number |
| `protocol` | string | Yes | Port protocol |

