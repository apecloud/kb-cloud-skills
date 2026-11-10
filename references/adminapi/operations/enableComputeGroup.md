# POST /admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/computeGroups/enable

**Resource:** [computeGroup](../resources/computeGroup.md)
**Enable a compute group on an existing component**
**Operation ID:** `enableComputeGroup`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | Engine name. |
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [computeGroupEnable](../schemas/computeGroupEnable/computeGroupEnable.md)

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

