# GET /admin/v1/environments/{environmentName}/engines/{engineName}

**Resource:** [engine](../resources/engine.md)
**Get engine in environment**
**Operation ID:** `getEngineByNameInEnv`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the EnvironmentName |
| `engineName` | path | string | Yes | name of the engine |
| `version` | query | string | Yes | engine version |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[engine](../schemas/engine/engine.md)

