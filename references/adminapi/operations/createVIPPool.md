# POST /admin/v1/environments/{environmentName}/loadbalancer/vipPool

**Resource:** [vipPool](../resources/vipPool.md)
**Create environment VIP Pool**
**Operation ID:** `createVIPPool`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [vipPoolCreate](../schemas/vipPoolCreate/vipPoolCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned when environment is created successfully. |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[vipPool](../schemas/vipPool/vipPool.md)

