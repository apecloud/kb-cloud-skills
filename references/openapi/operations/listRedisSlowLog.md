# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/redis/slowlog

**Resource:** [dms](../resources/dms.md)
**list Redis slow log entries**
**Operation ID:** `listRedisSlowLog`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `id` | path | string | Yes |  |
| `database` | query | integer (int64) | No | Logical Redis database index. SlowLog is server-level; the parameter is accepted for API consistency. |
| `limit` | query | integer (int64) | No |  |
| `nodeId` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[RedisSlowLogList](../schemas/Redis/RedisSlowLogList.md)

