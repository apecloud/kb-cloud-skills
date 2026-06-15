# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/offlineInstances

**Resource:** [cluster](../resources/cluster.md)
**List offline cluster instances**
**Operation ID:** `listOfflineInstance`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[offlineInstanceList](../schemas/offlineInstanceList/offlineInstanceList.md)

