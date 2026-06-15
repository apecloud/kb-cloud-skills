# POST /admin/v1/organizations/{orgName}/recycleBin/clusters/{clusterName}/restore

**Resource:** [recycleBinCluster](../resources/recycleBinCluster.md)
**Restore cluster from the Recycle Bin of the Org**
**Operation ID:** `restoreRecycleBinCluster`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[cluster](../schemas/cluster/cluster.md)

