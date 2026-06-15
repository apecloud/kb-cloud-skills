# GET /admin/v1/administrators/roles/{roleName}

**Resource:** [administrator](../resources/administrator.md)
**Get an administrator role by name**
**Operation ID:** `getAdministratorsRoleByName`

Get detailed information about a specific administrator role

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

[adminRole](../schemas/adminRole/adminRole.md)

