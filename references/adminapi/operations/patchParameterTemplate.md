# PATCH /admin/v1/parameterTemplate/{parameterTemplateName}

**Resource:** [parameterTemplate](../resources/parameterTemplate.md)
**Update parameter template**
**Operation ID:** `patchParameterTemplate`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | query | string | Yes | name of the Org |
| `parameterTemplateName` | path | string | Yes | name of the parameter template |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [paramTplUpdate](../schemas/paramTplUpdate/paramTplUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[paramTplListItem](../schemas/paramTplListItem/paramTplListItem.md)

