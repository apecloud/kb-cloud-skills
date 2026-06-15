# MongoCollectionStats

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | collection name |
| `type` | string | No | collection type (collection or view) |
| `isSystem` | boolean | No | whether this is a MongoDB system collection |
| `capabilities` | [MongoCollectionCapabilities](MongoCollectionCapabilities.md) | No |  |
| `documentCount` | integer (int64) | No |  |
| `totalSize` | integer (int64) | No |  |
| `indexCount` | integer (int64) | No |  |

