# cluster

KubeBlocks cluster details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | Cluster ID |
| `parentId` | string | No | When two clusters have a relationship, parentId records the parent cluster id.Can be empty when there is no relationship |
| `parentName` | string | No | the name of parent cluster |
| `parentDisplayName` | string | No | the display name of parent cluster |
| `clusterType` | [clusterType](clusterType.md) | No |  |
| `delay` | number (double) | No |  |
| `orgName` | string | No | Org Name |
| `cloudProvider` | string | No | Cloud Provider |
| `environmentId` | string | No | ID of the environment |
| `environmentName` | string | Yes | Environment Name |
| `cloudRegion` | string | No | Cloud Region |
| `project` | string | No | Name of project, it is the alias of environment namespace |
| `name` | string | Yes | Name of cluster. Name must be unique within an Org |
| `hash` | string | No | Hash of cluster. Name must be unique within an Org |
| `engine` | string | Yes | Cluster Application Engine |
| `license` | [clusterLicense](clusterLicense.md) | No |  |
| `paramTpls` | [paramTpls](paramTpls.md) | No |  |
| `version` | string | No | Cluster Application Version |
| `terminationPolicy` | [clusterTerminationPolicy](clusterTerminationPolicy.md) | No |  |
| `tlsEnabled` | boolean | No | Enable the cluster to provide TLS connection or not. |
| `nodePortEnabled` | boolean | No | Enable the cluster to provide NodePort service or not. |
| `status` | string | No | Cluster Status |
| `createdAt` | string (date-time) | No | CreatedAt is a timestamp representing the server time when this object was created. It is not guaranteed to be set in happens-before order across separate operations. Clients may not set this value. It is represented in RFC3339 form and is in UTC. Populated by the system. Read-only. Null for lists |
| `updatedAt` | string (date-time) | No | UpdatedAt is a timestamp representing the server time when this object was created. It is not guaranteed to be set in happens-before order across separate operations. Clients may not set this value. It is represented in RFC3339 form and is in UTC. Populated by the system. Read-only. Null for lists |
| `mode` | string | No | Cluster topology mode |
| `proxyEnabled` | boolean | No | Proxy Enabled |
| `components` | [components](components.md) | No |  |
| `extra` | object | No | Extra configuration for cluster |
| `initOptions` | [initOptions](initOptions.md) | No |  |
| `singleZone` | boolean | No | Use single availability zones |
| `availabilityZones` | string[] | No | Availability Zones |
| `podAntiAffinityEnabled` | boolean | No | Enable pod antiaffinity for cluster |
| `backup` | [clusterBackup](clusterBackup.md) | No |  |
| `nodeGroup` | string | No | Specify a NodeGroup for the cluster |
| `codeShort` | string | No | Cluster main component codeShort |
| `displayName` | string | No | Display name of cluster. |
| `static` | boolean | No | if cluster is static cluster |
| `networkMode` | [networkMode](networkMode.md) | No |  |
| `serviceRefs` | serviceRef[] | No | serviceRefs used by this cluster |
| `referencedBy` | serviceRef[] | No | this list of objects (currently, object is a cluster) that uses this cluster as a serviceRef |
| `objectStorageConfig` | [clusterObjectStorageConfig](clusterObjectStorageConfig.md) | No |  |
| `maintainceWindow` | [clusterMaintainceWindow](clusterMaintainceWindow.md) | No |  |
| `schedulingPolicy` | [schedulingPolicyType](schedulingPolicyType.md) | No |  |

