# PATCH /admin/v1/engines/{engineName}/schedulingPolicies

**Resource:** [engine](../resources/engine.md)
**Patch engine scheduling policy**
**Operation ID:** `patchEngineSchedulingPolicy`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | engine name |
| `engineMode` | query | string | Yes | filter by engine mode |

## Request Body

**Content Types:** `application/json`

**Schema:** [engineSchedulingPolicy](../schemas/engineSchedulingPolicy/engineSchedulingPolicy.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[engineSchedulingPolicy](../schemas/engineSchedulingPolicy/engineSchedulingPolicy.md)

