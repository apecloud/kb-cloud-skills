# POST /api/v1/organizations/{orgName}/parameters

**Resource:** [organizationParameter](../resources/organizationParameter.md)
**Batch update parameters of an organization**
**Operation ID:** `batchUpdateOrgParameters`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The name of the organization |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [orgParameterList](../schemas/orgParameterList/orgParameterList.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[orgParameterList](../schemas/orgParameterList/orgParameterList.md)

