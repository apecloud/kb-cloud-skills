# POST /admin/v1/parameterTemplates

**Resource:** [parameterTemplate](../resources/parameterTemplate.md)
**Create parameter template**
**Operation ID:** `createParameterTemplate`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | query | string | Yes | name of the Org |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [paramTplCreate](../schemas/paramTplCreate/paramTplCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | create parameter template successfully |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[paramTplListItem](../schemas/paramTplListItem/paramTplListItem.md)

