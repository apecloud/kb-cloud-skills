# clusterUpdate

ClusterUpdate is the payload to update a KubeBlocks cluster

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `terminationPolicy` | [clusterTerminationPolicy](clusterTerminationPolicy.md) | No |  |
| `displayName` | string | No | Display name of cluster. |
| `maintainceWindow` | [clusterMaintainceWindow](clusterMaintainceWindow.md) | No |  |
| `newServiceRefs` | serviceRef[] | No | ServiceRefs to add to the cluster. Each serviceRef must be supported
by the current engine mode and must not duplicate the existing
serviceRefs of the cluster.
 |
| `serviceRefsUpdate` | serviceRef[] | No | ServiceRefs to update. Each serviceRef name must match an existing
serviceRef of the cluster, and the corresponding engine option
modeServiceRef.update.enable must be true. ServiceRefs that auto
create their ServiceDescriptor and Secret get their corresponding
K8s objects updated; serviceRefs with manual input must be handled
by each engine individually and are rejected.
 |

