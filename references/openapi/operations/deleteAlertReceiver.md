# DELETE /api/v1/organizations/{orgName}/receivers/{receiverId}

**Resource:** [alertReceiver](../resources/alertReceiver.md)
**Delete alert receiver**
**Operation ID:** `deleteAlertReceiver`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `receiverId` | path | string | Yes | id of the alert receivers |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when project is deleted successfully. |
| 403 | (reference) |
| 404 | (reference) |

