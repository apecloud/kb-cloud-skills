# POST /api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/computeGroups

**Resource:** [computeGroup](../resources/computeGroup.md)
**Create compute group**
**Operation ID:** `createComputeGroup`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | Supported engine name (doris or selectdb). |
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [computeGroupCreate](../schemas/computeGroupCreate/computeGroupCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted; poll taskId for convergence. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

