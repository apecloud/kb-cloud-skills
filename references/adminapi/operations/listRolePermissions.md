# GET /admin/v1/organizations/{orgName}/roles/{roleName}/permissions

**Resource:** [role](../resources/role.md)
**List permissions of a role**
**Operation ID:** `listRolePermissions`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `roleName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[permissionList](../schemas/permissionList/permissionList.md)

