# PUT /admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/computeGroups/{groupName}/accounts/{accountName}/default

**Resource:** [computeGroup](../resources/computeGroup.md)
**Set default compute group**
**Operation ID:** `setDefaultComputeGroup`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | Supported engine name (doris or selectdb). |
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `groupName` | path | string | Yes |  |
| `accountName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Updated |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

