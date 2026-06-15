# GET /admin/v1/alerts/receivers

**Resource:** [alertReceiver](../resources/alertReceiver.md)
**List alert receivers**
**Operation ID:** `listAlertReceivers`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `category` | query | alertReceiverCategory | No | alert receiver category |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[alertReceiverList](../schemas/alertReceiverList/alertReceiverList.md)

