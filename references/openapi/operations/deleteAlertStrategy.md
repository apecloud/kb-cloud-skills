# DELETE /api/v1/organizations/{orgName}/alerts/strategies/{strategyId}

**Resource:** [alertStrategy](../resources/alertStrategy.md)
**Delete alert strategy**
**Operation ID:** `deleteAlertStrategy`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `strategyId` | path | string | Yes | id of the alert strategies |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when project is deleted successfully. |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

