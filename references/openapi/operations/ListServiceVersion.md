# GET /api/v1/environments/{environmentName}/engines/{engineName}/serviceVersion

**Resource:** [engine](../resources/engine.md)
**list the service version of the engine**
**Operation ID:** `ListServiceVersion`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | environment name |
| `engineName` | path | string | Yes | Name of the engine |
| `engineMode` | query | string | Yes | engine mode |
| `engineVersion` | query | string | Yes | engine version |
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

