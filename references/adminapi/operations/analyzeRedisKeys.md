# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/redis/analysis

**Resource:** [dms](../resources/dms.md)
**analyze Redis keys by bounded SCAN sampling**
**Operation ID:** `analyzeRedisKeys`

Returns an instant sample analysis for Redis keys. The result is not a persisted or full historical report; callers must use progress.complete, progress.processed, progress.sampleLimit, and generatedAt to present the sampling boundary.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `id` | path | string | Yes |  |
| `database` | query | integer (int64) | No |  |
| `match` | query | string | No | Redis SCAN match pattern. |
| `cursor` | query | string | No | Cursor returned by a previous analysis scan. Empty starts a new sample scan. |
| `sampleLimit` | query | integer (int64) | No | Maximum number of keys to sample in this analysis request. |
| `topN` | query | integer (int64) | No | Maximum number of top keys or namespaces to return. |
| `namespaceSeparator` | query | string | No | Separator used to group key namespaces. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | analyze redis key sample success |

**Success Response Schema:**

[RedisAnalysisResponse](../schemas/Redis/RedisAnalysisResponse.md)

