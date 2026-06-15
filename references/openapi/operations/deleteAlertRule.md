# DELETE /api/v1/organizations/{orgName}/alerts/rules/{alertName}

**Resource:** [alertRule](../resources/alertRule.md)
**Delete alert rule**
**Operation ID:** `deleteAlertRule`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `alertName` | path | string | Yes | id of the alert rules |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when project is deleted successfully. |
| 403 | (reference) |
| 404 | (reference) |

