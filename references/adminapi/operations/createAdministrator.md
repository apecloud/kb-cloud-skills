# POST /admin/v1/administrators

**Resource:** [administrator](../resources/administrator.md)
**Create a new administrator**
**Operation ID:** `createAdministrator`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [userCreate](../schemas/userCreate/userCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | (reference) |
| 401 | (reference) |
| 409 | (reference) |

**Success Response Schema:**

[user](../schemas/user/user.md)

