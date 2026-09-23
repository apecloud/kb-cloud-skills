# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/redis/pubsub/sessions/{sessionId}/messages

**Resource:** [dms](../resources/dms.md)
**list messages from a Redis Pub/Sub polling session**
**Operation ID:** `listRedisPubSubMessages`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `id` | path | string | Yes |  |
| `sessionId` | path | string | Yes |  |
| `cursor` | query | string | No |  |
| `limit` | query | integer (int64) | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[RedisPubSubMessageList](../schemas/Redis/RedisPubSubMessageList.md)

