# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/redis/keys

**Resource:** [dms](../resources/dms.md)
**list Redis key summaries by SCAN cursor**
**Operation ID:** `listRedisKeys`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `id` | path | string | Yes |  |
| `database` | query | integer (int64) | No | Logical Redis database index. Redis Cluster only supports 0. |
| `cursor` | query | string | No |  |
| `limit` | query | integer (int64) | No |  |
| `pattern` | query | string | No |  |
| `type` | query | string | No |  |
| `separator` | query | string | No |  |
| `nodeId` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[RedisKeySummaryList](../schemas/Redis/RedisKeySummaryList.md)

