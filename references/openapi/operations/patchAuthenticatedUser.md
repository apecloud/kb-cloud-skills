# PATCH /api/v1/user

**Resource:** [user](../resources/user.md)
**Update user information**
**Operation ID:** `patchAuthenticatedUser`

partially update the specified User. If you want to update phone number, you must request /api/v1/user/phone-verification-code first.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [userUpdate](../schemas/userUpdate/userUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 204 | Returned when project is deleted successfully. |
| 401 | (reference) |

**Success Response Schema:**

[user](../schemas/user/user.md)

