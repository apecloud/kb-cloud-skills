# GET /admin/v1/engines/{engineName}/schedulingPolicies

**Resource:** [engine](../resources/engine.md)
**List engine scheduling policies**
**Operation ID:** `listEngineSchedulingPolicies`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | engine name |
| `engineMode` | query | string | No | filter by engine mode |
| `env` | query | string | No | environment name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [engineSchedulingPolicy](../schemas/engineSchedulingPolicy/engineSchedulingPolicy.md)

