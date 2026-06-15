# POST /admin/v1/alerts/rules

**Resource:** [alertRule](../resources/alertRule.md)
**Create alert rule**
**Operation ID:** `createAlertRule`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `disabled` | query | boolean | No | disabled status |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [alertRule](../schemas/alertRule/alertRule.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[alertRule](../schemas/alertRule/alertRule.md)

