# clusterLog

Cluster Log APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/logs/running` | Query cluster running logs | [View](../operations/queryRunningLogs.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/logs/slow` | Query cluster slow logs | [View](../operations/querySlowLogs.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/logs/slow/explain` | Explain cluster slow log SQL | [View](../operations/explainSlowLog.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/logs/slow/templates` | Query cluster slow log templates | [View](../operations/querySlowLogTemplates.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/logs/slow/templates/{templateId}` | Get cluster slow log template | [View](../operations/getSlowLogTemplate.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/logs/slow/templates/{templateId}/explain` | Explain cluster slow log template | [View](../operations/explainSlowLogTemplate.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/logs/slow/templates/{templateId}/samples` | Query cluster slow log template samples | [View](../operations/querySlowLogTemplateSamples.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/logs/slow/aggregate` | Aggregate cluster slow logs | [View](../operations/aggregateSlowLogs.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/logs/slow/stats` | Get cluster slow log statistics | [View](../operations/getSlowLogStats.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/logs/audit` | Query cluster audit logs | [View](../operations/queryAuditLogs.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/logs/audit/aggregate` | Aggregate cluster audit logs | [View](../operations/aggregateAuditLogs.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/logs/hits` | Query log hits histogram | [View](../operations/queryLogHits.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/logs/error` | Query cluster error logs | [View](../operations/queryErrorLogs.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/logs/pod` | Query cluster pod logs | [View](../operations/queryPodLogs.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/logs/export` | Export cluster logs | [View](../operations/exportClusterLogs.md) |
