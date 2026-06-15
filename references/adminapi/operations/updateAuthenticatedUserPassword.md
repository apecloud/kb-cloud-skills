# PATCH /admin/v1/user/password

**Resource:** [user](../resources/user.md)
**Update current authenticated user password**
**Operation ID:** `updateAuthenticatedUserPassword`

Update current authenticated user password.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `new_password` | string | Yes | The new password for the user. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Password updated successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

