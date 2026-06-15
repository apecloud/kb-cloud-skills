# POST /admin/v1/engines/{engineName}/schedulingRules

**Resource:** [engine](../resources/engine.md)
**Create engine scheduling rule**
**Operation ID:** `createEngineSchedulingRule`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | engine name |

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

