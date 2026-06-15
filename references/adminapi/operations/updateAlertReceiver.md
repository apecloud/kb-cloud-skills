# PATCH /admin/v1/alerts/receivers/{receiverId}

**Resource:** [alertReceiver](../resources/alertReceiver.md)
**Update alert receiver**
**Operation ID:** `updateAlertReceiver`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `receiverId` | path | string | Yes | receiver id |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [alertReceiver](../schemas/alertReceiver/alertReceiver.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned when project is deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[alertReceiver](../schemas/alertReceiver/alertReceiver.md)

