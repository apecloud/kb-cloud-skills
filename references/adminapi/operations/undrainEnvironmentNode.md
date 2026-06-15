# POST /admin/v1/environments/{environmentName}/nodes/{nodeName}/undrain

**Resource:** [environment](../resources/environment.md)
**Undrain environment node**
**Operation ID:** `undrainEnvironmentNode`

Undrain the specified Environment node. This action will remove the NoExecute taint and make the node schedulable again.

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

