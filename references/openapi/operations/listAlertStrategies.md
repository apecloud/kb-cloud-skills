# GET /api/v1/organizations/{orgName}/alerts/strategies

**Resource:** [alertStrategy](../resources/alertStrategy.md)
**List alert strategies**
**Operation ID:** `listAlertStrategies`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[alertStrategyList](../schemas/alertStrategyList/alertStrategyList.md)

