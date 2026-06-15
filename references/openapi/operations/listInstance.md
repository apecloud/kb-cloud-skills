# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/instances

**Resource:** [cluster](../resources/cluster.md)
**List cluster instances**
**Operation ID:** `listInstance`

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

[instanceList](../schemas/instanceList/instanceList.md)

