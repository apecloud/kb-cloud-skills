# GET /admin/v1/environments/{environmentName}/engines

**Resource:** [engine](../resources/engine.md)
**List engines in environment**
**Operation ID:** `listEnginesInEnv`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the EnvironmentName |
| `name` | query | string | No | engine name |
| `type` | query | string | No | engine Type |
| `version` | query | string | No | engine version |
| `provider` | query | string | No | engine provider |
| `all` | query | boolean | No | list all engines include uninstall engines |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[engineList](../schemas/engineList/engineList.md)

