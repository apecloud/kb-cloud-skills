# DELETE /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/redis/pubsub/sessions/{sessionId}

**Resource:** [dms](../resources/dms.md)
**close a Redis Pub/Sub polling session**
**Operation ID:** `closeRedisPubSubSession`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `id` | path | string | Yes |  |
| `sessionId` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | session closed |

