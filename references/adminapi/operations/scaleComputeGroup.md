# POST /admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/computeGroups/{groupName}/scale

**Resource:** [computeGroup](../resources/computeGroup.md)
**Scale compute group**
**Operation ID:** `scaleComputeGroup`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | Supported engine name (doris or selectdb). |
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `groupName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [computeGroupScale](../schemas/computeGroupScale/computeGroupScale.md)

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

