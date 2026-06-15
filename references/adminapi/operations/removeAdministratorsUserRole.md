# DELETE /admin/v1/administrators/{administratorID}/roles/{roleName}

**Resource:** [administrator](../resources/administrator.md)
**Remove a role from an administrator user**
**Operation ID:** `removeAdministratorsUserRole`

Remove a specific role from an administrator user

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `administratorID` | path | string | Yes |  |
| `roleName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when role is removed successfully. |
| 401 | (reference) |
| 404 | (reference) |

