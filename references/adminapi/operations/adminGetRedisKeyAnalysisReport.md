# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/redis/keyAnalysis/{taskId}

**Resource:** [redisKeyAnalysis](../resources/redisKeyAnalysis.md)
**Get a Redis keys analysis report**
**Operation ID:** `adminGetRedisKeyAnalysisReport`

Returns one persisted row per shard plus one non-persisted aggregate row with
isSummary=true when more than one row is returned.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `taskId` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Report rows plus an optional aggregate row. |
| 404 | (reference) |

**Success Response Schema:**

Array of [RedisKeyAnalysisReport](../schemas/Redis/RedisKeyAnalysisReport.md)

