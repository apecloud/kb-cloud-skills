# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/rebuildInstance/availableNodes

**Resource:** [opsrequest](../resources/opsrequest.md)
**List available nodes for rebuilding instance**
**Operation ID:** `listAvailableNodes`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |
| `name` | query | string | Yes | name of the instance to be rebuilt |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Accepted |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[nodeList](../schemas/nodeList/nodeList.md)

