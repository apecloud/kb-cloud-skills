# damengTableSizeItem

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `schema` | string | Yes | Schema (owner) name. |
| `tableName` | string | Yes | Table name. |
| `sizeBytes` | integer (int64) | Yes | Total segment size in bytes for this table. |
| `rowCount` | integer (int64) | No | Estimated number of rows from DBA_TABLES.NUM_ROWS. |

