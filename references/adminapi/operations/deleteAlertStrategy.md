# DELETE /admin/v1/alerts/strategies/{strategyId}

**Resource:** [alertStrategy](../resources/alertStrategy.md)
**Delete alert strategy**
**Operation ID:** `deleteAlertStrategy`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `strategyId` | path | string | Yes | id of the alert strategy |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when project is deleted successfully. |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

