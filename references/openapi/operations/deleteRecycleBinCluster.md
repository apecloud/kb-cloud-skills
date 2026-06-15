# DELETE /api/v1/organizations/{orgName}/recycleBin/clusters/{clusterName}

**Resource:** [recycleBinCluster](../resources/recycleBinCluster.md)
**Delete cluster from the Recycle Bin of the Org**
**Operation ID:** `deleteRecycleBinCluster`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `isDeleteBackup` | query | boolean | Yes | whether to delete the backup of the cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

