# GET /admin/v1/parameterTemplate/{parameterTemplateName}

**Resource:** [parameterTemplate](../resources/parameterTemplate.md)
**Get parameter template details**
**Operation ID:** `readParameterTemplate`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | query | string | Yes | name of the Org |
| `parameterTemplateName` | path | string | Yes | name of the parameter template |
| `partition` | query | parameterTemplatePartition | No | the template partition in read paramTpl request |
| `rawContent` | query | boolean | No | whether to return the raw template content |

## Responses

| Status | Description |
|--------|-------------|
| 200 | read parameter template successfully |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[parameterList](../schemas/parameterList/parameterList.md)

