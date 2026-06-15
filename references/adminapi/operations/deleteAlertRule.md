# DELETE /admin/v1/alerts/rules/{alertName}

**Resource:** [alertRule](../resources/alertRule.md)
**Delete alert rule**
**Operation ID:** `deleteAlertRule`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `alertName` | path | string | Yes | name of the alert rule |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Delete successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

