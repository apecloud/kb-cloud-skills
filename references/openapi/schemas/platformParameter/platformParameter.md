# platformParameter

platformParameter item

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | platformParameter ID |
| `name` | string | Yes | platformParameter name |
| `category` | [platformParameterCategory](platformParameterCategory.md) | Yes |  |
| `type` | string | Yes | type of platformParameter value |
| `constraints` | object | Yes | platformParameter constraints including min, max, enum, default value |
| `value` | string | No | platformParameter value |
| `description` | [localizedDescription](localizedDescription.md) | Yes |  |

## Nested Fields

### `constraints`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `min` | string | No | platformParameter min value |
| `max` | string | No | platformParameter max value |
| `enum` | string[] | No | platformParameter enum constraints |
| `default` | string | No | platformParameter default value |

