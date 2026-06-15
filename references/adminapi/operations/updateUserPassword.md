# PATCH /admin/v1/users/{userID}/password

**Resource:** [user](../resources/user.md)
**Update user password**
**Operation ID:** `updateUserPassword`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `userID` | path | string | Yes | ID of the user |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [password](../schemas/password/password.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Password updated successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

