# PATCH /admin/v1/organizations/{orgName}/parameters/{parameterName}

**Resource:** [organizationParameter](../resources/organizationParameter.md)
**Update a parameter of an organization**
**Operation ID:** `patchOrgParameter`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The name of the organization |
| `parameterName` | path | string | Yes | The name of the parameter |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [orgParameter](../schemas/orgParameter/orgParameter.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[orgParameter](../schemas/orgParameter/orgParameter.md)

