# PATCH /api/v1/organizations/{orgName}/alerts/objects/{alertId}

**Resource:** [alertObject](../resources/alertObject.md)
**Set alert object status**
**Operation ID:** `setAlertObjectStatus`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `alertId` | path | string | Yes | alert id |
| `status` | query | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[alertObject](../schemas/alertObject/alertObject.md)

