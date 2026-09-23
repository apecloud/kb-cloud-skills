# mysqlTableSpace

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `database` | string | Yes |  |
| `name` | string | Yes |  |
| `engine` | string | Yes |  |
| `rows` | integer (int64) | Yes | Estimated row count for InnoDB tables. |
| `dataBytes` | integer (int64) | Yes |  |
| `indexBytes` | integer (int64) | Yes |  |
| `freeBytes` | integer (int64) | Yes |  |
| `totalBytes` | integer (int64) | Yes |  |
| `avgRowLength` | integer (int64) | Yes |  |
| `fragmentationRatio` | number (double) | No | freeBytes divided by totalBytes plus freeBytes when available. |
| `createTime` | string | No |  |
| `updateTime` | string | No |  |

