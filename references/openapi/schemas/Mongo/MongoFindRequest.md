# MongoFindRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `filter` | object | No | MongoDB query filter |
| `sort` | object | No | sort specification |
| `projection` | object | No | field projection |
| `collation` | object | No | MongoDB collation options |
| `skip` | integer (int64) | No | number of documents to skip |
| `limit` | integer (int64) | No | maximum number of documents to return |
| `maxTimeMS` | integer (int64) | No | maximum query execution time in milliseconds |

