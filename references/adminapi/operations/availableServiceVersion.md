# GET /admin/v1/environments/{environmentName}/engines/{engineName}/availableServiceVersion

**Resource:** [engine](../resources/engine.md)
**list the service version of the engine**
**Operation ID:** `availableServiceVersion`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | environment name |
| `engineName` | path | string | Yes | Name of the engine |
| `component` | query | string | No | component type, refer to componentDef and support NamePrefix |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[engineServiceVersions](../schemas/engineServiceVersions/engineServiceVersions.md)

