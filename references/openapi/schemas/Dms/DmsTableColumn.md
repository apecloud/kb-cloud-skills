# DmsTableColumn

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | The name of the column |
| `type` | string | No | The data type of the column |
| `length` | integer | No | The length of the column if applicable |
| `scale` | integer | No | The number of decimal places for numeric columns |
| `notNull` | boolean | No | Whether the column can be null |
| `default` | string | No | The default value for the column |
| `comment` | string | No | A comment describing the column |
| `autoIncrement` | boolean | No | Whether the column is auto-incremented |
| `seed` | integer | No | used for autoIncrement |
| `increment` | integer | No | used for autoIncrement |
| `unsigned` | boolean | No | Whether the column is unsigned |
| `onUpdateCurrentTimestamp` | boolean | No | Whether the column updates to the current timestamp on update |
| `hidden` | boolean | No | Whether the column is hidden |
| `generated` | object | No | Generated column information |

## Nested Fields

### `generated`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | string | No | The type of generation (e.g., VIRTUAL or STORED) |
| `expression` | string | No | The expression used to generate the column's value |

