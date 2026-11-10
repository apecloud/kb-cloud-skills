# PUT /admin/v1/environments/{environmentName}/loadbalancer/vipPool/{poolID}

**Resource:** [vipPool](../resources/vipPool.md)
**Update environment VIP Pool**
**Operation ID:** `updateVIPPool`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |
| `poolID` | path | string | Yes | id of the VIP Pool |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [vipPoolUpdate](../schemas/vipPoolUpdate/vipPoolUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[vipPool](../schemas/vipPool/vipPool.md)

