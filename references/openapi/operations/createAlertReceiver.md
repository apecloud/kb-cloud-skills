# POST /api/v1/organizations/{orgName}/receivers

**Resource:** [alertReceiver](../resources/alertReceiver.md)
**Create alert receiver**
**Operation ID:** `createAlertReceiver`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `category` | query | alertReceiverCategory | Yes | alert receiver category |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [alertReceiver](../schemas/alertReceiver/alertReceiver.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[alertReceiver](../schemas/alertReceiver/alertReceiver.md)

