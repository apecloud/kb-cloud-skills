# DELETE /api/v1/organizations/{orgName}/roles/{roleName}

**Resource:** [role](../resources/role.md)
**Delete role by name**
**Operation ID:** `deleteRoleByName`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `roleName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when role is deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

