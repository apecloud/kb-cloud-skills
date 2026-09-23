# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/redis/pubsub/publish

**Resource:** [dms](../resources/dms.md)
**publish a Redis Pub/Sub message**
**Operation ID:** `publishRedisMessage`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `id` | path | string | Yes |  |
| `database` | query | integer (int64) | No | Logical Redis database index for this Pub/Sub client. Redis Pub/Sub is server-level, but the client connection is still scoped to the selected DB for consistency. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [RedisPubSubPublishRequest](../schemas/Redis/RedisPubSubPublishRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[RedisOperationSummary](../schemas/Redis/RedisOperationSummary.md)

