# PATCH /admin/v1/users/{userID}

**Resource:** [user](../resources/user.md)
**Update the information of the specified user**
**Operation ID:** `patchUser`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `userID` | path | string | Yes | ID of the user |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [userUpdate](../schemas/userUpdate/userUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[user](../schemas/user/user.md)

