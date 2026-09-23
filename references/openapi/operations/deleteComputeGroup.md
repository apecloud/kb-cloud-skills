# DELETE /api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/computeGroups/{groupName}

**Resource:** [computeGroup](../resources/computeGroup.md)
**Delete compute group**
**Operation ID:** `deleteComputeGroup`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | Supported engine name (doris or selectdb). |
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `groupName` | path | string | Yes |  |

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

