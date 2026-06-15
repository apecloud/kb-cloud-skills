# DELETE /admin/v1/environments/{environmentName}/loadbalancer/vipPool/{poolID}

**Resource:** [vipPool](../resources/vipPool.md)
**Delete environment VIP Pool**
**Operation ID:** `deleteVIPPool`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |
| `poolID` | path | string | Yes | id of the VIP Pool |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when project is deleted successfully. |
| 403 | (reference) |
| 404 | (reference) |

