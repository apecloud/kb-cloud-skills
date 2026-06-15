# GET /admin/v1/administrators/roles/{roleName}/permissions

**Resource:** [administrator](../resources/administrator.md)
**List permissions of an administrator role**
**Operation ID:** `listAdministratorsRolePermissions`

List all permissions assigned to a specific administrator role

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `roleName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[adminPermissionList](../schemas/adminPermissionList/adminPermissionList.md)

