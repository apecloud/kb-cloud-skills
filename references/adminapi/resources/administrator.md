# administrator

Administrator APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/administrators` | List administrators | [View](../operations/listAdministrators.md) |
| POST | `/admin/v1/administrators` | Create a new administrator | [View](../operations/createAdministrator.md) |
| DELETE | `/admin/v1/administrators/{administratorID}` | delete administrator | [View](../operations/deleteAdministrator.md) |
| PATCH | `/admin/v1/administrators/{administratorID}` | Update the information of the specified administrator | [View](../operations/patchAdministrator.md) |
| PATCH | `/admin/v1/administrators/{administratorID}/password` | Update administrator password | [View](../operations/updateAdministratorPassword.md) |
| GET | `/admin/v1/administrators/{administratorID}/roles` | List roles of an administrator user | [View](../operations/listAdministratorsUserRoles.md) |
| POST | `/admin/v1/administrators/{administratorID}/roles` | Add a role to an administrator user | [View](../operations/addAdministratorsUserRole.md) |
| DELETE | `/admin/v1/administrators/{administratorID}/roles/{roleName}` | Remove a role from an administrator user | [View](../operations/removeAdministratorsUserRole.md) |
| GET | `/admin/v1/administrators/permissions` | List all permissions for administrators | [View](../operations/listAdministratorsPermissions.md) |
| GET | `/admin/v1/administrators/roles` | List all administrator roles | [View](../operations/listAdministratorsRoles.md) |
| POST | `/admin/v1/administrators/roles` | Create an administrator role | [View](../operations/createAdministratorsRole.md) |
| GET | `/admin/v1/administrators/roles/{roleName}` | Get an administrator role by name | [View](../operations/getAdministratorsRoleByName.md) |
| DELETE | `/admin/v1/administrators/roles/{roleName}` | Delete an administrator role by name | [View](../operations/deleteAdministratorsRoleByName.md) |
| PATCH | `/admin/v1/administrators/roles/{roleName}` | Update an administrator role by name | [View](../operations/updateAdministratorsRoleByName.md) |
| GET | `/admin/v1/administrators/roles/{roleName}/permissions` | List permissions of an administrator role | [View](../operations/listAdministratorsRolePermissions.md) |
| POST | `/admin/v1/administrators/roles/{roleName}/permissions/batch` | Batch add permissions to an administrator role | [View](../operations/batchAddAdministratorsRolePermissions.md) |
| DELETE | `/admin/v1/administrators/roles/{roleName}/permissions/batch` | Batch remove permissions from an administrator role | [View](../operations/batchRemoveAdministratorsRolePermissions.md) |
