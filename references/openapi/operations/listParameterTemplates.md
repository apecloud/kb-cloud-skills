# GET /api/v1/organizations/{orgName}/parameterTemplates

**Resource:** [parameterTemplate](../resources/parameterTemplate.md)
**List parameter templates in an Org**
**Operation ID:** `listParameterTemplates`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `partition` | query | parameterTemplatePartition | No | the template partition in listParamTpl request |
| `version` | query | string | No | Cluster Application Version |
| `component` | query | string | No | component type |
| `engineName` | query | string | No | engine Name |
| `engineMode` | query | string | No | engine mode |

## Responses

| Status | Description |
|--------|-------------|
| 200 | list parameter templates successfully |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[paramTplList](../schemas/paramTplList/paramTplList.md)

