# MongoRBACRoleWrite

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `role` | string | Yes |  |
| `db` | string | Yes |  |
| `privileges` | MongoRBACPrivilege[] | Yes |  |
| `roles` | MongoRBACRoleRef[] | Yes |  |
| `expectedRevision` | string | No |  |

