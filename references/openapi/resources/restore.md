# restore

Restore APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v1/organizations/{orgName}/clustersWithDelete/restoreTimeRange` | Get cluster restore time ragne | [View](../operations/getRestoreTimeRange.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/restore` | List restore tasks | [View](../operations/listClusterRestore.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/restore` | Restore current cluster or instance | [View](../operations/doRestore.md) |
| DELETE | `/api/v1/organizations/{orgName}/clusters/{clusterName}/restore` | Delete restore task | [View](../operations/deleteRestoreObject.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/restore/{restoreId}/logs` | get restore workload logs of the cluster | [View](../operations/GetRestoreLog.md) |
| GET | `/api/v1/organizations/{orgName}/restore` | List restore tasks | [View](../operations/listRestores.md) |
| POST | `/api/v1/organizations/{orgName}/restore` | Restore new cluster | [View](../operations/restoreCluster.md) |
