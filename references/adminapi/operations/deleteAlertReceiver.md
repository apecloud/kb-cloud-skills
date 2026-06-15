# DELETE /admin/v1/alerts/receivers/{receiverId}

**Resource:** [alertReceiver](../resources/alertReceiver.md)
**Delete alert receiver**
**Operation ID:** `deleteAlertReceiver`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `receiverId` | path | string | Yes | receiver id |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when alert receiver is deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

