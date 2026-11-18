# POST /api/v1/environments/{environmentName}/loadbalancer/vipPool/checkPorts

**Resource:** [vipPool](../resources/vipPool.md)
**Check whether ports are already used on a VIP**
**Operation ID:** `checkVIPPorts`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [vipPortCheckRequest](../schemas/vipPortCheckRequest/vipPortCheckRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[vipPortCheckResult](../schemas/vipPortCheckResult/vipPortCheckResult.md)

