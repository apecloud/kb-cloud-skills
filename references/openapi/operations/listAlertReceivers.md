# GET /api/v1/organizations/{orgName}/receivers

**Resource:** [alertReceiver](../resources/alertReceiver.md)
**List alert receivers**
**Operation ID:** `listAlertReceivers`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
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

