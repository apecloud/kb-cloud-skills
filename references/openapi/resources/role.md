# role

Role Management APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v1/organizations/{orgName}/permissions` | List permissions of a member | [View](../operations/listOrgMemberPermission.md) |
| GET | `/api/v1/permissions` | List all permissions | [View](../operations/listPermissions.md) |
| GET | `/api/v1/organizations/{orgName}/roles` | List roles of a organization | [View](../operations/listRoles.md) |
| POST | `/api/v1/organizations/{orgName}/roles` | Create role | [View](../operations/createRole.md) |
| GET | `/api/v1/organizations/{orgName}/roles/{roleName}` | Get role by name | [View](../operations/getRoleByName.md) |
| DELETE | `/api/v1/organizations/{orgName}/roles/{roleName}` | Delete role by name | [View](../operations/deleteRoleByName.md) |
| PATCH | `/api/v1/organizations/{orgName}/roles/{roleName}` | Update role by name | [View](../operations/updateRoleByName.md) |
| GET | `/api/v1/organizations/{orgName}/roles/{roleName}/permissions` | List permissions of a role | [View](../operations/listRolePermissions.md) |
| POST | `/api/v1/organizations/{orgName}/roles/{roleName}/permissions/batch` | Batch add permissions to a role | [View](../operations/batchAddRolePermissions.md) |
| DELETE | `/api/v1/organizations/{orgName}/roles/{roleName}/permissions/batch` | Batch remove permissions from a role | [View](../operations/batchRemoveRolePermissions.md) |
