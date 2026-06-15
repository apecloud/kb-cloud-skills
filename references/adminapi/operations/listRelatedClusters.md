# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/relations

**Resource:** [relation](../resources/relation.md)
**list the clusters that have built a relation to the specified cluster**
**Operation ID:** `listRelatedClusters`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | list the clusters that have built relations to the cluster |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[relatedClusterList](../schemas/relatedClusterList/relatedClusterList.md)

