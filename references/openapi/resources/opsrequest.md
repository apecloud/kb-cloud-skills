# opsrequest

Cluster Ops APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/reconfigure` | Update cluster configuration | [View](../operations/reconfigureCluster.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/stop` | Stop cluster | [View](../operations/stopCluster.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/start` | Start cluster | [View](../operations/startCluster.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/restart` | Restart cluster | [View](../operations/restartCluster.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/rebuildInstance` | rebuild the instance | [View](../operations/rebuildInstance.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/rebuildInstance/availableNodes` | List available nodes for rebuilding instance | [View](../operations/listAvailableNodes.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/upgrade` | Upgrade cluster version | [View](../operations/upgradeCluster.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/volume-expand` | Expand cluster volume size | [View](../operations/clusterVolumeExpand.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/vscale` | Vertical scale cluster | [View](../operations/verticalScaleCluster.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/hscale` | Horizontal scale cluster | [View](../operations/horizontalScaleCluster.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/promote` | Promote cluster intance to primary | [View](../operations/promoteCluster.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/expose` | Expose cluster loadbalancer endpoint | [View](../operations/exposeCluster.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/updateLicense` | Update the cluster license | [View](../operations/updateClusterLicense.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/custom-ops` | Create custom OpsRequest | [View](../operations/customOps.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/volumes/io-quotas` | Specify IOPS and BPS of cluster volumes | [View](../operations/specifyClusterIOQuotas.md) |
