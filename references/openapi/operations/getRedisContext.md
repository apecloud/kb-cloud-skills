# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/redis/context

**Resource:** [dms](../resources/dms.md)
**get Redis datasource data-management context**
**Operation ID:** `getRedisContext`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `id` | path | string | Yes |  |
| `database` | query | integer (int64) | No | Current logical Redis database index for this context. Omitted uses the datasource default; Redis Cluster only supports 0. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[RedisDataContext](../schemas/Redis/RedisDataContext.md)

