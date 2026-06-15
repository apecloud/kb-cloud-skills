# POST /api/v1/user/apikeys

**Resource:** [user](../resources/user.md)
**Create apikey of the authenticated user**
**Operation ID:** `createUserApikey`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [apikeyCreate](../schemas/apikeyCreate/apikeyCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | A successful response. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[apikeyWithSK](../schemas/apikeyWithSK/apikeyWithSK.md)

