# MongoRBACBindingChange

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | string | Yes | grant or revoke. Incremental; all other native roles are retained. |
| `roles` | MongoRBACRoleRef[] | Yes |  |

