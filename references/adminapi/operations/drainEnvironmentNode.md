# POST /admin/v1/environments/{environmentName}/nodes/{nodeName}/drain

**Resource:** [environment](../resources/environment.md)
**Drain environment node**
**Operation ID:** `drainEnvironmentNode`

Drain the specified Environment node. This action will evict all pods from the node and mark it as unschedulable.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |
| `nodeName` | path | string | Yes | name of the environment node |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

