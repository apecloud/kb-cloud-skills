# POST /admin/v1/parameterTemplates

**Resource:** [parameterTemplate](../resources/parameterTemplate.md)
**Create parameter template**
**Operation ID:** `createParameterTemplate`

Create a parameter template in the target organization from an existing template. To copy a custom template from another organization, specify oriOrgName and provide a new name. Cross-organization creation only supports non-private custom source templates. The created template is always non-private; any isPrivate value in the request body is ignored.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | query | string | Yes | Name of the target organization |
| `oriOrgName` | query | string | No | Name of the source organization. When omitted, empty, or equal to orgName, existing creation behavior is preserved: custom templates are read from the target organization and default templates from the system organization. A different source organization requires oriPartition to be custom and name to differ from oriName. Both organizations must be active. The source may be the system organization, but the target must not be the system organization. A non-empty value containing only whitespace is invalid. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [paramTplCreate](../schemas/paramTplCreate/paramTplCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | create parameter template successfully |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |

**Success Response Schema:**

[paramTplListItem](../schemas/paramTplListItem/paramTplListItem.md)

