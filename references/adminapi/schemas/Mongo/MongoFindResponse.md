# MongoFindResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `columns` | string[] | No | column names (flattened document key union) |
| `rows` | array[] | No | row data (flattened document values) |
| `documents` | object[] | No | raw documents (when raw mode) |
| `totalCount` | integer (int64) | No | total matching documents |

