# GET /api/v1/engines/resourceConstraints

**Resource:** [engine](../resources/engine.md)
**List engine resource constraints**
**Operation ID:** `listEngineResourceConstraints`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engine` | query | string | No | engine name |
| `mode` | query | string | No | engine mode |
| `component` | query | string | No | engine component |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[resourceConstraintList](../schemas/resourceConstraintList/resourceConstraintList.md)

