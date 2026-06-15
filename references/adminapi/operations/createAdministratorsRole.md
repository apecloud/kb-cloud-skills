# POST /admin/v1/administrators/roles

**Resource:** [administrator](../resources/administrator.md)
**Create an administrator role**
**Operation ID:** `createAdministratorsRole`

Create a custom administrator role

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [adminRoleCreate](../schemas/adminRoleCreate/adminRoleCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | (reference) |
| 401 | (reference) |

**Success Response Schema:**

[adminRole](../schemas/adminRole/adminRole.md)

