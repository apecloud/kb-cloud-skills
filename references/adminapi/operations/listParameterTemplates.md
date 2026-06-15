# GET /admin/v1/parameterTemplates

**Resource:** [parameterTemplate](../resources/parameterTemplate.md)
**List parameter templates**
**Operation ID:** `listParameterTemplates`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | query | string | No | name of the Org |
| `partition` | query | parameterTemplatePartition | No | the template partition in listParameterTemplates request |
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

