# GET /admin/v1/environments/{environmentName}/network/ipPools

**Resource:** [environment](../resources/environment.md)
**Discover Pod IP pools and explicit selection policy in an environment**
**Operation ID:** `listEnvironmentIPPools`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the Environment |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[ipPoolList](../schemas/ipPoolList/ipPoolList.md)

