# GET /api/v1/organizations/{orgName}/receivers/{receiverId}

**Resource:** [alertReceiver](../resources/alertReceiver.md)
**Get alert receiver**
**Operation ID:** `getAlertReceiver`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `receiverId` | path | string | Yes | id of the alert receivers |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |

**Success Response Schema:**

[alertReceiver](../schemas/alertReceiver/alertReceiver.md)

