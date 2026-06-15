# GET /admin/v1/organizations/{orgName}/recycleBin/clusters

**Resource:** [recycleBinCluster](../resources/recycleBinCluster.md)
**List clusters in the Recycle Bin of the Org**
**Operation ID:** `listRecycleBinCluster`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[recycleBinClusterList](../schemas/recycleBinClusterList/recycleBinClusterList.md)

