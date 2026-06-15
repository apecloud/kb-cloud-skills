# GET /admin/v1/engines/{engineName}/schedulingRules

**Resource:** [engine](../resources/engine.md)
**List engine scheduling rules**
**Operation ID:** `listEngineSchedulingRules`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | engine name |
| `engineMode` | query | string | No | filter by engine mode |
| `schedulingPolicyType` | query | string | No | filter by scheduling policy type |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [engineSchedulingRule](../schemas/engineSchedulingRule/engineSchedulingRule.md)

