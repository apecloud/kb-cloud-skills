# restore

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/organizations/{orgName}/clustersWithDelete/restoreTimeRange` | Get cluster restore time ragne | [View](../operations/getRestoreTimeRange.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/restore` | List restore tasks | [View](../operations/listClusterRestore.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/restore` | Restore current cluster or instance | [View](../operations/doRestore.md) |
| DELETE | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/restore` | Delete restore task | [View](../operations/deleteRestoreObject.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/restore/{restoreId}/logs` | get restore workload logs of the cluster | [View](../operations/GetRestoreLog.md) |
| GET | `/admin/v1/restoreTasks` | List restore tasks | [View](../operations/listRestores.md) |
| POST | `/admin/v1/organizations/{orgName}/restore` | Restore new cluster | [View](../operations/restoreCluster.md) |
