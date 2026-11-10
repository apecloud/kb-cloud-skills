# MongoRBACRole

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `role` | string | No |  |
| `db` | string | No |  |
| `isBuiltin` | boolean | No |  |
| `privileges` | MongoRBACPrivilege[] | No |  |
| `roles` | MongoRBACRoleRef[] | No |  |
| `inheritedRoles` | MongoRBACRoleRef[] | No |  |
| `inheritedPrivileges` | MongoRBACPrivilege[] | No |  |
| `revision` | string | No | Stale-form fingerprint. updateRole has no native CAS; external concurrent writes are not transactional. |

