# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/redis/keyAnalysis/{taskId}

**Resource:** [redisKeyAnalysis](../resources/redisKeyAnalysis.md)
**Get a Redis keys analysis report**
**Operation ID:** `getRedisKeyAnalysisReport`

Returns one persisted row per shard. For a cluster with multiple shards, one
additional aggregate row with isSummary=true is appended; it is not persisted.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `taskId` | path | string | Yes | Platform TaskFlow task ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Report rows plus an optional aggregate row. |
| 404 | (reference) |

**Success Response Schema:**

Array of [RedisKeyAnalysisReport](../schemas/Redis/RedisKeyAnalysisReport.md)

