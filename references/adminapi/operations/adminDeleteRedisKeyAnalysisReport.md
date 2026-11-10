# DELETE /admin/v1/organizations/{orgName}/clusters/{clusterName}/redis/keyAnalysis/{taskId}

**Resource:** [redisKeyAnalysis](../resources/redisKeyAnalysis.md)
**Delete a Redis keys analysis report**
**Operation ID:** `adminDeleteRedisKeyAnalysisReport`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `taskId` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Report deleted. |
| 404 | (reference) |

