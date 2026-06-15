# opsrequest

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/reconfigure` | Update cluster configuration | [View](../operations/reconfigureCluster.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/restart` | Restart cluster | [View](../operations/restartCluster.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/rebuildInstance` | rebuild the instance | [View](../operations/rebuildInstance.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/rebuildInstance/availableNodes` | List available nodes for rebuilding instance | [View](../operations/listAvailableNodes.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/upgrade` | Upgrade cluster version | [View](../operations/upgradeCluster.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/volume-expand` | Expand cluster volume size | [View](../operations/clusterVolumeExpand.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/vscale` | Vertical scale cluster | [View](../operations/verticalScaleCluster.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/hscale` | Horizontal scale cluster | [View](../operations/horizontalScaleCluster.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/promote` | Promote cluster intance to primary | [View](../operations/promoteCluster.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/stop` | Stop cluster | [View](../operations/stopCluster.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/start` | Start cluster | [View](../operations/startCluster.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/expose` | Expose cluster loadbalancer endpoint | [View](../operations/exposeCluster.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/updateLicense` | Update the cluster license | [View](../operations/updateClusterLicense.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/custom-ops` | Create custom OpsRequest | [View](../operations/customOps.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/volumes/io-quotas` | Specify IOPS and BPS of cluster volumes | [View](../operations/specifyClusterIOQuotas.md) |
