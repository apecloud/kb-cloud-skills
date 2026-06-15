# PATCH /admin/v1/administrators/{administratorID}/password

**Resource:** [administrator](../resources/administrator.md)
**Update administrator password**
**Operation ID:** `updateAdministratorPassword`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `administratorID` | path | string | Yes | ID of the administrator |

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

