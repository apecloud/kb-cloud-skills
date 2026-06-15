# GET /admin/v1/organizations/{orgName}/parameters/{parameterName}

**Resource:** [organizationParameter](../resources/organizationParameter.md)
**Get a parameter of an organization**
**Operation ID:** `getOrgParameter`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The name of the organization |
| `parameterName` | path | string | Yes | The name of the parameter |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[orgParameter](../schemas/orgParameter/orgParameter.md)

