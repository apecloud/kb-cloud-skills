# cluster

Cluster APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v1/organizations/{orgName}/clusters` | List clusters in the Org | [View](../operations/listCluster.md) |
| POST | `/api/v1/organizations/{orgName}/clusters` | Create new cluster | [View](../operations/createCluster.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/batch` | Batch update clusters | [View](../operations/batchUpdateClusters.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/validate` | Validate cluster creation | [View](../operations/validateClusterCreation.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}` | Get cluster details | [View](../operations/getCluster.md) |
| DELETE | `/api/v1/organizations/{orgName}/clusters/{clusterName}` | Delete cluster | [View](../operations/deleteCluster.md) |
| PATCH | `/api/v1/organizations/{orgName}/clusters/{clusterName}` | Update cluster specified fields | [View](../operations/patchCluster.md) |
| GET | `/api/v1/organizations/{orgName}/clustersWithDelete/{clusterID}` | Get cluster details by ID | [View](../operations/getClusterByID.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/instances` | List cluster instances | [View](../operations/listInstance.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/offlineInstances` | List offline cluster instances | [View](../operations/listOfflineInstance.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/instances/{instanceName}/restart` | Restart instance of cluster | [View](../operations/restartInstance.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/instances/{instanceName}/events` | List instance events | [View](../operations/listInstanceEvents.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/instances/{instanceName}/log` | Tail cluster instance container log | [View](../operations/getInstanceContainerLog.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/workloads/{workloadName}/log` | Tail cluster instance container log | [View](../operations/getClusterInstanceLog.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/haHistory` | describe cluster HA history | [View](../operations/describeClusterHaHistory.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/modeTransition` | Transition cluster engine mode | [View](../operations/transitionClusterMode.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/endpoints` | List cluster endpoints | [View](../operations/listEndpoints.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/sqlAudit` | Get SQL audit log status | [View](../operations/getSqlAudit.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/sqlAudit` | Update SQL audit log status | [View](../operations/updateSqlAudit.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/tde` | Get TDE status | [View](../operations/getTDE.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/tde` | Enable TDE | [View](../operations/updateTDE.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/metrics` | Query cluster metrics | [View](../operations/queryClusterMetrics.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/instances/metrics` | Get instaces metrics in cluster | [View](../operations/getInstacesMetrics.md) |
