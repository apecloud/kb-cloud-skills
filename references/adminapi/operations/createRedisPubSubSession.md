# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/redis/pubsub/sessions

**Resource:** [dms](../resources/dms.md)
**create a Redis Pub/Sub polling session**
**Operation ID:** `createRedisPubSubSession`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `id` | path | string | Yes |  |
| `database` | query | integer (int64) | No | Logical Redis database index for the polling client connection. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [RedisPubSubSessionCreateRequest](../schemas/Redis/RedisPubSubSessionCreateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | session created |

**Success Response Schema:**

[RedisPubSubSession](../schemas/Redis/RedisPubSubSession.md)

