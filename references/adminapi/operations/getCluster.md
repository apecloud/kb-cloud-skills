# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}

**Resource:** [cluster](../resources/cluster.md)
**Get cluster details**
**Operation ID:** `getCluster`

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
| 404 | (reference) |
| 409 | (reference) |

**Success Response Schema:**

[cluster](../schemas/cluster/cluster.md)

