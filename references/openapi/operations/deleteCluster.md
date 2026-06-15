# DELETE /api/v1/organizations/{orgName}/clusters/{clusterName}

**Resource:** [cluster](../resources/cluster.md)
**Delete cluster**
**Operation ID:** `deleteCluster`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |
| `force` | query | boolean | No | if it is true, the cluster will be deleted no matter what the termination policy is, and will not be moved to the recycle bin. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when project is deleted successfully. |
| 403 | (reference) |
| 404 | (reference) |

