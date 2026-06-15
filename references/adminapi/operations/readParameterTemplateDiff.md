# GET /admin/v1/parameterTemplate/{parameterTemplateName}/diff

**Resource:** [parameterTemplate](../resources/parameterTemplate.md)
**Get parameter template diff against default template**
**Operation ID:** `readParameterTemplateDiff`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | query | string | Yes | name of the Org |
| `parameterTemplateName` | path | string | Yes | name of the parameter template |
| `partition` | query | parameterTemplatePartition | No | the template partition in diff parameter template request |
| `rawContent` | query | boolean | No | whether to compare raw template content |

## Responses

| Status | Description |
|--------|-------------|
| 200 | get parameter template diff successfully |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |

**Success Response Schema:**

[parameterTemplateDiff](../schemas/parameterTemplateDiff/parameterTemplateDiff.md)

