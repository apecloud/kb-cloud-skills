# GET /admin/v1/users/{userID}/authorization

**Resource:** [user](../resources/user.md)
**Get user roles in multiple organizations**
**Operation ID:** `getUserAuthorization`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `userID` | path | string | Yes | ID of the user |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [userAuthorization](../schemas/userAuthorization/userAuthorization.md)

