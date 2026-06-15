# PATCH /admin/v1/administrators/{administratorID}

**Resource:** [administrator](../resources/administrator.md)
**Update the information of the specified administrator**
**Operation ID:** `patchAdministrator`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `administratorID` | path | string | Yes | ID of the administrator |

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

