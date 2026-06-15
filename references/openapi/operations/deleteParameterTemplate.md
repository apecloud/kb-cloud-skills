# DELETE /api/v1/organizations/{orgName}/parameterTemplate/{parameterTemplateName}

**Resource:** [parameterTemplate](../resources/parameterTemplate.md)
**Delete parameter template**
**Operation ID:** `deleteParameterTemplate`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `parameterTemplateName` | path | string | Yes | name of the parameter template |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when project is deleted successfully. |
| 403 | (reference) |
| 404 | (reference) |

