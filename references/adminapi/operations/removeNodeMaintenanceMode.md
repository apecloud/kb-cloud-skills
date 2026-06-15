# PATCH /admin/v1/environments/{environmentName}/nodes/{nodeName}/maintenance/off

**Resource:** [environment](../resources/environment.md)
**Remove the node from maintenance mode**
**Operation ID:** `removeNodeMaintenanceMode`

Remove the node from maintenance mode. This action restores the node to its normal operational state, allowing it to resume handling workloads.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |
| `nodeName` | path | string | Yes | name of the environment node |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[jsonBody](../schemas/jsonBody/jsonBody.md)

