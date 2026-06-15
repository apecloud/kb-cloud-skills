# DELETE /admin/v1/administrators/roles/{roleName}

**Resource:** [administrator](../resources/administrator.md)
**Delete an administrator role by name**
**Operation ID:** `deleteAdministratorsRoleByName`

Delete a custom administrator role

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `roleName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when role is deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

