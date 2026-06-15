# PATCH /api/v1/organizations/{orgName}/receivers/{receiverId}

**Resource:** [alertReceiver](../resources/alertReceiver.md)
**Update alert receiver**
**Operation ID:** `patchAlertReceiver`

partially update the alert receiver

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `receiverId` | path | string | Yes | id of the alert receivers |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [alertReceiver](../schemas/alertReceiver/alertReceiver.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned when project is deleted successfully. |
| 401 | (reference) |

**Success Response Schema:**

[alertReceiver](../schemas/alertReceiver/alertReceiver.md)

