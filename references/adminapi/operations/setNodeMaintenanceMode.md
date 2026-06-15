# PATCH /admin/v1/environments/{environmentName}/nodes/{nodeName}/maintenance/on

**Resource:** [environment](../resources/environment.md)
**Set the node to maintenance mode**
**Operation ID:** `setNodeMaintenanceMode`

Set the node to maintenance mode. This action temporarily disables the node for maintenance activities, ensuring no new workloads are scheduled on it.

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

