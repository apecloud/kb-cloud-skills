# GET /admin/v1/environments/{environmentName}/engineOptions

**Resource:** [engine](../resources/engine.md)
**List environment engine options**
**Operation ID:** `listEnvironmentEngineOptions`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | environment name |
| `engineName` | query | string | No | filter by engine name |
| `mode` | query | string | No | filter by engine mode |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[environmentEngineOptionList](../schemas/environmentEngineOptionList/environmentEngineOptionList.md)

