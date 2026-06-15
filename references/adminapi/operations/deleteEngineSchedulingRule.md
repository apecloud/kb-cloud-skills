# DELETE /admin/v1/engines/{engineName}/schedulingRules/{ruleId}

**Resource:** [engine](../resources/engine.md)
**Delete engine scheduling rule**
**Operation ID:** `deleteEngineSchedulingRule`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | engine name |
| `ruleId` | path | string | Yes | id of the engine scheduling rule |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when engine scheduling rule is deleted successfully. |
| 403 | (reference) |
| 404 | (reference) |

