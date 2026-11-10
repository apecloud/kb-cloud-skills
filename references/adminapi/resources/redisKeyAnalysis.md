# redisKeyAnalysis

Redis Keys Analysis APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/redis/keyAnalysis` | Create a Redis keys analysis task | [View](../operations/adminCreateRedisKeyAnalysis.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/redis/keyAnalysis/{taskId}` | Get a Redis keys analysis report | [View](../operations/adminGetRedisKeyAnalysisReport.md) |
| DELETE | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/redis/keyAnalysis/{taskId}` | Delete a Redis keys analysis report | [View](../operations/adminDeleteRedisKeyAnalysisReport.md) |
