# vipPortCheckRequest

VIP port check request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ip` | string | Yes | VIP address to check |
| `ports` | integer[] | No | TCP ports to check. When empty, only the occupied ports are returned. |

