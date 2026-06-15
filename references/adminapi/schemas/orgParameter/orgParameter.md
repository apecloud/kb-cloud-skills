# orgParameter

org parameter item

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | org parameter id |
| `orgId` | string | Yes | org id |
| `name` | string | Yes | org parameter name |
| `category` | string | Yes | org parameter category |
| `type` | string | Yes | type of org parameter value |
| `constraints` | object | Yes | org parameter constraints including min, max, enum, default value |
| `description` | [localizedDescription](localizedDescription.md) | Yes |  |
| `value` | string | Yes | org parameter value |

## Nested Fields

### `constraints`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `min` | string | No | org parameter min value |
| `max` | string | No | org parameter max value |
| `enum` | string[] | No | org parameter enum constraints |
| `default` | string | No | org parameter default value |

