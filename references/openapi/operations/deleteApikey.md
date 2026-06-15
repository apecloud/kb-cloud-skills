# DELETE /api/v1/user/apikey/{keyName}

**Resource:** [user](../resources/user.md)
**Delete apikey**
**Operation ID:** `deleteApikey`

delete apikey

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `keyName` | path | string | Yes | Name of the Apikey |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when apikey is deleted successfully. |
| 401 | (reference) |
| 404 | (reference) |

