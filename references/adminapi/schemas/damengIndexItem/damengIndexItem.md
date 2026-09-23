# damengIndexItem

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `schema` | string | Yes | Schema (owner) name. |
| `indexName` | string | Yes | Index name. |
| `tableName` | string | Yes | Parent table name. |
| `sizeBytes` | integer (int64) | Yes | Segment size in bytes from DBA_SEGMENTS. |
| `indexType` | string | No | Index type (e.g. NORMAL, BITMAP, CLUSTER). |
| `isUnique` | boolean | Yes | Whether the index enforces uniqueness. |

