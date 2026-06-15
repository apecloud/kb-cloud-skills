# GET /admin/v1/organizations/{orgName}/parameters

**Resource:** [organizationParameter](../resources/organizationParameter.md)
**List parameters of an organization**
**Operation ID:** `listOrgParameters`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The name of the organization |
| `category` | query | string | No | the category of the parameters |
| `name` | query | string | No | the name of the parameter |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[orgParameterList](../schemas/orgParameterList/orgParameterList.md)

