# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/redis/key/detail

**Resource:** [dms](../resources/dms.md)
**get Redis key detail**
**Operation ID:** `getRedisKeyDetail`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `id` | path | string | Yes |  |
| `database` | query | integer (int64) | No | Logical Redis database index. Redis Cluster only supports 0. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [RedisKeyDetailRequest](../schemas/Redis/RedisKeyDetailRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[RedisKeyDetail](../schemas/Redis/RedisKeyDetail.md)

