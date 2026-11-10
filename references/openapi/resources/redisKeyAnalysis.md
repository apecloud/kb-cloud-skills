# redisKeyAnalysis

Redis Keys Analysis APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/redis/keyAnalysis` | Create a Redis keys analysis task | [View](../operations/createRedisKeyAnalysis.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/redis/keyAnalysis/{taskId}` | Get a Redis keys analysis report | [View](../operations/getRedisKeyAnalysisReport.md) |
| DELETE | `/api/v1/organizations/{orgName}/clusters/{clusterName}/redis/keyAnalysis/{taskId}` | Delete a Redis keys analysis report | [View](../operations/deleteRedisKeyAnalysisReport.md) |
