# role

Role Management APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/permissions` | List all permissions | [View](../operations/listPermissions.md) |
| GET | `/admin/v1/organizations/{orgName}/roles` | List roles of a organization | [View](../operations/listRoles.md) |
| POST | `/admin/v1/organizations/{orgName}/roles` | Create role | [View](../operations/createRole.md) |
| GET | `/admin/v1/organizations/{orgName}/roles/{roleName}` | Get role by name | [View](../operations/getRoleByName.md) |
| DELETE | `/admin/v1/organizations/{orgName}/roles/{roleName}` | Delete role by name | [View](../operations/deleteRoleByName.md) |
| PATCH | `/admin/v1/organizations/{orgName}/roles/{roleName}` | Update role by name | [View](../operations/updateRoleByName.md) |
| GET | `/admin/v1/organizations/{orgName}/roles/{roleName}/permissions` | List permissions of a role | [View](../operations/listRolePermissions.md) |
| POST | `/admin/v1/organizations/{orgName}/roles/{roleName}/permissions/batch` | Batch add permissions to a role | [View](../operations/batchAddRolePermissions.md) |
| DELETE | `/admin/v1/organizations/{orgName}/roles/{roleName}/permissions/batch` | Batch remove permissions from a role | [View](../operations/batchRemoveRolePermissions.md) |
