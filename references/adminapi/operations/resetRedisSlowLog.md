# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/redis/slowlog/reset

**Resource:** [dms](../resources/dms.md)
**reset Redis slow log**
**Operation ID:** `resetRedisSlowLog`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `id` | path | string | Yes |  |
| `database` | query | integer (int64) | No | Logical Redis database index. SlowLog reset is server-level; the parameter is accepted for API consistency. |

## Request Body

**Content Types:** `application/json`

**Schema:** [RedisDangerousOperationRequest](../schemas/Redis/RedisDangerousOperationRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[RedisOperationSummary](../schemas/Redis/RedisOperationSummary.md)

