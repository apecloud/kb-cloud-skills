# MongoRBACResource

Native MongoDB resource. cluster:true is system operations, not all database data. Empty db/collection are explicit wildcard scopes; system collections need explicit resources.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cluster` | boolean | No |  |
| `db` | string | No | Preserve an explicit empty string for native wildcard scope; omit only for cluster resources. |
| `collection` | string | No | Preserve an explicit empty string for native wildcard scope; omit only for cluster resources. |
| `anyResource` | boolean | No | Read-only native evidence; write requests reject this internal resource. |

