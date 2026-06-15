# GET /api/v1/organizations/{orgName}/alerts/rules/{alertName}

**Resource:** [alertRule](../resources/alertRule.md)
**Operation ID:** `getAlertRule`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `alertName` | path | string | Yes | name of the alert |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

