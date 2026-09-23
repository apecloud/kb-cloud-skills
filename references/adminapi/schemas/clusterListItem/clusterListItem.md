# clusterListItem

KubeBlocks cluster information

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cloudProvider` | string | Yes | Cloud Provider |
| `cloudRegion` | string | No | Cloud Provider |
| `availabilityZones` | string[] | No | Availability Zones |
| `createdAt` | string (date-time) | Yes | CreatedAt is a timestamp representing the server time when this object was created. It is not guaranteed to be set in happens-before order across separate operations. Clients may not set this value. It is represented in RFC3339 form and is in UTC. Populated by the system. Read-only. Null for lists |
| `displayName` | string | No | Display name of cluster. |
| `engine` | string | Yes | Cluster Application Engine |
| `mode` | string | No | Cluster topology mode |
| `environmentName` | string | Yes | Environment Name |
| `environmentDisplayName` | string | No | Environment Display Name |
| `id` | string | Yes | ID of cluster |
| `name` | string | Yes | Name of cluster. Name must be unique within an Org |
| `parentId` | string | No | When two clusters have a relationship, parentId records the parent cluster id.Can be empty when there is no relationship |
| `parentName` | string | No | the name of parent cluster |
| `parentDisplayName` | string | No | the display name of parent cluster |
| `dependencyType` | string | No | the dependency relationship between the cluster and the refClusterName
query parameter. `Dependency` means the cluster is referenced by the
refClusterName cluster (the refClusterName depends on it); `Dependent`
means the cluster references the refClusterName cluster (it depends on
the refClusterName). Only set when list clusters with refClusterName.
 |
| `dependencyLabel` | object | No | the localized title of the serviceRef through which the refClusterName
cluster depends on the returned cluster. Only set for clusters with
dependencyType `Dependency`.
 |
| `clusterType` | [clusterType](clusterType.md) | No |  |
| `delay` | number (double) | No |  |
| `status` | string | Yes | Cluster Status |
| `terminationPolicy` | string | Yes | Cluster termination policy |
| `updatedAt` | string (date-time) | Yes | UpdatedAt is a timestamp representing the server time when this object was created. It is not guaranteed to be set in happens-before order across separate operations. Clients may not set this value. It is represented in RFC3339 form and is in UTC. Populated by the system. Read-only. Null for lists |
| `version` | string | Yes | Cluster Application Version |
| `classCode` | string | No | Cluster main component classCode |
| `storage` | string | No | Cluster main component storage |
| `codeShort` | string | No | Cluster main component codeShort |
| `orgName` | string | No | Org Name |
| `project` | string | No | Name of project, it is the alias of environment namespace |
| `tags` | tag[] | No | Tags bound to the cluster |
| `endpoints` | endpoint[] | No | Cached user-visible endpoints of the cluster; omitted unless includeEndpoints is true |

