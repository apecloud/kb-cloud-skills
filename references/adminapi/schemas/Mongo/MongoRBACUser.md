# MongoRBACUser

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `db` | string | No |  |
| `roles` | MongoRBACRoleRef[] | No |  |
| `inheritedRoles` | MongoRBACRoleRef[] | No |  |
| `inheritedPrivileges` | MongoRBACPrivilege[] | No |  |
| `user` | string | No |  |
| `readOnly` | boolean | No | Platform-protected account; mutations are rejected. |

