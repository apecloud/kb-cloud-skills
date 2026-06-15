# MongoCreateCollectionOptions

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `capped` | boolean | No |  |
| `size` | integer (int64) | No | capped collection size in bytes |
| `max` | integer (int64) | No | capped collection max document count |
| `validator` | object | No | collection validator document |
| `validationLevel` | string | No |  |
| `validationAction` | string | No |  |
| `collation` | object | No | default collection collation |

