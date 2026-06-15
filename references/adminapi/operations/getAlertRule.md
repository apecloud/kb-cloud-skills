# GET /admin/v1/alerts/rules/{alertName}

**Resource:** [alertRule](../resources/alertRule.md)
**Get alert rule**
**Operation ID:** `getAlertRule`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `alertName` | path | string | Yes | name of the alert rule |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[alertRule](../schemas/alertRule/alertRule.md)

