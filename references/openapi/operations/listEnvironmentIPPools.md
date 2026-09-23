# GET /api/v1/organizations/{orgName}/environments/{environmentName}/network/ipPools

**Resource:** [environment](../resources/environment.md)
**Discover Pod IP pools and explicit selection policy in an environment**
**Operation ID:** `listEnvironmentIPPools`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `environmentName` | path | string | Yes | name of the Environment |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[ipPoolList](../schemas/ipPoolList/ipPoolList.md)

