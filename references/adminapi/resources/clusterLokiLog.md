# clusterLokiLog

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/logs/loki/pod` | Query Loki pod logs | [View](../operations/queryLokiPodLogs.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/logs/loki/running` | Query Loki running logs | [View](../operations/queryLokiRunningLogs.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/logs/loki/error` | Query Loki error logs | [View](../operations/queryLokiErrorLogs.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/logs/loki/slow` | Query Loki slow logs | [View](../operations/queryLokiSlowLogs.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/logs/loki/audit` | Query Loki audit logs | [View](../operations/queryLokiAuditLogs.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/logs/loki/slow/stats` | Query Loki slow-log statistics | [View](../operations/getLokiSlowLogStats.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/logs/loki/export` | Export Loki logs | [View](../operations/exportLokiClusterLogs.md) |
