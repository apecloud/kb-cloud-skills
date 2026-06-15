# GET /admin/v1/environments/{environmentName}/nodes/{nodeName}/instances/resourceStats

**Resource:** [resourceStats](../resources/resourceStats.md)
**Get resource statistics of instances**
**Operation ID:** `listInstancesResourceStats`

Returns aggregated resource statistics for the specified node.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | The name of the environment |
| `nodeName` | path | string | Yes | The name of the node |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[instanceResourceStatsList](../schemas/instanceResourceStatsList/instanceResourceStatsList.md)

