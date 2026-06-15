# PATCH /api/v1/user/apikey/{keyName}

**Resource:** [user](../resources/user.md)
**Update apikey information**
**Operation ID:** `patchAPIkey`

partially update the specified apikey

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `keyName` | path | string | Yes | Name of the apikey |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [apikeyCreate](../schemas/apikeyCreate/apikeyCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |

**Success Response Schema:**

[apikey](../schemas/apikey/apikey.md)

