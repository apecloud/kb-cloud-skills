# MongoUpdateRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `filter` | object | No | document selector |
| `update` | object | No | update document |
| `upsert` | boolean | No | create document when no match exists |
| `many` | boolean | No | reserved for future bulk update; S1 rejects true |

