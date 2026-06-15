# PATCH /admin/v1/administrators/roles/{roleName}

**Resource:** [administrator](../resources/administrator.md)
**Update an administrator role by name**
**Operation ID:** `updateAdministratorsRoleByName`

Update a custom administrator role

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `roleName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [adminRoleUpdate](../schemas/adminRoleUpdate/adminRoleUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[adminRole](../schemas/adminRole/adminRole.md)

