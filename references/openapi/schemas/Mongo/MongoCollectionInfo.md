# MongoCollectionInfo

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | collection or view name |
| `type` | string | No | collection type (collection or view) |
| `isSystem` | boolean | No | whether this is a MongoDB system collection |
| `capabilities` | [MongoCollectionCapabilities](MongoCollectionCapabilities.md) | No |  |
| `options` | object | No | collection options, including viewOn/pipeline when type is view |

