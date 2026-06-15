# GET /admin/v1/environments/{environmentName}/nodes

**Resource:** [environment](../resources/environment.md)
**List Kubernetes nodes in an environment**
**Operation ID:** `listNodes`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |
| `hostName` | query | string | No | Hostname to filter by |
| `outOfTopologyRange` | query | boolean | No | List nodes with invalid region & zone labels |
| `labelKey` | query | string | No | List nodes with label |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A list of nodes |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[nodeList](../schemas/nodeList/nodeList.md)

