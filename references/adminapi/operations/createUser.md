# POST /admin/v1/users

**Resource:** [user](../resources/user.md)
**Create a new user**
**Operation ID:** `createUser`

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

