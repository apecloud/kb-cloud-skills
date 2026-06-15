# DELETE /admin/v1/environments/{environmentName}/nodeGroups/{nodeGroupName}

**Resource:** [environment](../resources/environment.md)
**Delete environment node group**
**Operation ID:** `deleteNodeGroup`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |
| `nodeGroupName` | path | string | Yes | name of the node group |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when project is deleted successfully. |
| 403 | (reference) |
| 404 | (reference) |

