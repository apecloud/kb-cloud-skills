# PATCH /admin/v1/engines/{engineName}/schedulingRules/{ruleId}

**Resource:** [engine](../resources/engine.md)
**Patch engine scheduling rule**
**Operation ID:** `patchEngineSchedulingRule`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | engine name |
| `ruleId` | path | string | Yes | id of the engine scheduling rule |

## Request Body

**Content Types:** `application/json`

**Schema:** [engineSchedulingRule](../schemas/engineSchedulingRule/engineSchedulingRule.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[engineSchedulingRule](../schemas/engineSchedulingRule/engineSchedulingRule.md)

