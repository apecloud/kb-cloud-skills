# ImportTaskCreateRequest

Create import task request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | Import name |
| `sourceType` | [ImportSourceType](ImportSourceType.md) | Yes |  |
| `connectionConfig` | object | Yes | Connection configuration |
| `objectSelection` | [dataChannelObject](dataChannelObject.md) | No |  |

