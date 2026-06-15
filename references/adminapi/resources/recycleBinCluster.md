# recycleBinCluster

Recycle Bin Cluster APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/recycleBin/clusters` | List all clusters in the Recycle Bin | [View](../operations/listRecycleBinClusters.md) |
| GET | `/admin/v1/organizations/{orgName}/recycleBin/clusters` | List clusters in the Recycle Bin of the Org | [View](../operations/listRecycleBinCluster.md) |
| GET | `/admin/v1/organizations/{orgName}/recycleBin/clusters/{clusterName}` | Get cluster in the Recycle Bin of the Org | [View](../operations/getRecycleBinCluster.md) |
| DELETE | `/admin/v1/organizations/{orgName}/recycleBin/clusters/{clusterName}` | Delete cluster from the Recycle Bin of the Org | [View](../operations/deleteRecycleBinCluster.md) |
| POST | `/admin/v1/organizations/{orgName}/recycleBin/clusters/{clusterName}/restore` | Restore cluster from the Recycle Bin of the Org | [View](../operations/restoreRecycleBinCluster.md) |
