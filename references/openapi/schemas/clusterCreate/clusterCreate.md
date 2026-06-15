# clusterCreate

KubeBlocks cluster information

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `parentId` | string | No | When two clusters have a relationship, parentId records the parent cluster id.Can be empty when there is no relationship |
| `clusterType` | [clusterType](clusterType.md) | No |  |
| `orgName` | string | No | Org Name |
| `environmentName` | string | Yes | Environment Name |
| `project` | string | No | Name of project, it is the alias of environment namespace |
| `name` | string | Yes | Name of cluster. Name must be unique within an Org |
| `engine` | string | Yes | Cluster Application Engine |
| `license` | [clusterLicense](clusterLicense.md) | No |  |
| `paramTpls` | [paramTpls](paramTpls.md) | No |  |
| `version` | string | No | Cluster Application Version |
| `terminationPolicy` | [clusterTerminationPolicy](clusterTerminationPolicy.md) | No |  |
| `mode` | string | No | Cluster topology mode |
| `components` | [componentsCreate](componentsCreate.md) | No |  |
| `extra` | object | No | Extra configuration for cluster. This will be added to helm values to render the cluster chart. |
| `initOptions` | [initOptions](initOptions.md) | No |  |
| `singleZone` | boolean | No | Use single availability zones |
| `availabilityZones` | string[] | No | Availability Zones |
| `backup` | [clusterBackup](clusterBackup.md) | No |  |
| `nodeGroup` | string | No | Specify a NodeGroup for the cluster |
| `displayName` | string | No | Display name of cluster. |
| `static` | boolean | No | if cluster is static cluster |
| `networkMode` | [networkMode](networkMode.md) | No |  |
| `serviceRefs` | serviceRef[] | No |  |
| `objectStorageConfig` | [clusterObjectStorageConfig](clusterObjectStorageConfig.md) | No |  |
| `maintainceWindow` | [clusterMaintainceWindow](clusterMaintainceWindow.md) | No |  |
| `schedulingPolicy` | [schedulingPolicyType](schedulingPolicyType.md) | No |  |

