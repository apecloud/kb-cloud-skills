# PATCH /admin/v1/environments/{environmentName}/nodes/{nodeName}/uncordon

**Resource:** [environment](../resources/environment.md)
**Cordon environment node**
**Operation ID:** `uncordonEnvironmentNode`

cordon the specified Environment node

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

