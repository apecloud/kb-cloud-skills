# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/redis/key/mutate

**Resource:** [dms](../resources/dms.md)
**mutate Redis key data or metadata**
**Operation ID:** `mutateRedisKey`

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

**Schema:** [RedisKeyMutateRequest](../schemas/Redis/RedisKeyMutateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[RedisKeyMutateResponse](../schemas/Redis/RedisKeyMutateResponse.md)

