# MongoCreateViewRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | view name |
| `viewOn` | string | No | source collection name |
| `pipeline` | object[] | No | read-only aggregation pipeline backing the view |
| `collation` | object | No | optional view collation |

