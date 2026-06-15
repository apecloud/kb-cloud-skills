# GET /admin/v1/environments/{environmentName}/loadbalancer/vipPool

**Resource:** [vipPool](../resources/vipPool.md)
**List environment VIP Pools**
**Operation ID:** `listVIPPool`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[vipPoolList](../schemas/vipPoolList/vipPoolList.md)

