# MilvusRoleGrant

Native Milvus role privilege grant.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `dbName` | string | No | Milvus database name. Empty means Milvus default/global scope. |
| `collectionName` | string | No | Milvus collection name. Use '*' for all collections in the database. |
| `privilege` | string | Yes | Native Milvus privilege name, such as DatabaseReadOnly, DatabaseReadWrite, DatabaseAdmin, Search, Insert, or Delete. |

