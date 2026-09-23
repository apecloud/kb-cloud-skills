# ipPoolSelection

Provider-qualified Pod IP pool selection for component pod IP allocation.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `provider` | [ipPoolProvider](ipPoolProvider.md) | Yes |  |
| `ipv4Pools` | string[] | No | IPv4 pool names resolved within the selected provider. |
| `ipv6Pools` | string[] | No | IPv6 pool names resolved within the selected provider. |

