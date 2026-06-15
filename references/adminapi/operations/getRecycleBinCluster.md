# GET /admin/v1/organizations/{orgName}/recycleBin/clusters/{clusterName}

**Resource:** [recycleBinCluster](../resources/recycleBinCluster.md)
**Get cluster in the Recycle Bin of the Org**
**Operation ID:** `getRecycleBinCluster`

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

[recycleBinCluster](../schemas/recycleBinCluster/recycleBinCluster.md)

