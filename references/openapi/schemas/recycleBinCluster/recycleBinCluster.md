# recycleBinCluster

KubeBlocks cluster(in recycle bin) information

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | Cluster Recycle Bin ID |
| `clusterId` | string | No | Cluster ID |
| `orgName` | string | No | Org Name |
| `cloudProvider` | string | No | Cloud Provider |
| `environmentId` | string | No | ID of the environment |
| `environmentName` | string | Yes | Environment Name |
| `environmentType` | string | No | Environment Types |
| `cloudRegion` | string | No | Cloud Region |
| `namespace` | string | No | Environment Namespace |
| `name` | string | Yes | Name of cluster. Name must be unique within an Org |
| `hash` | string | No | Hash of cluster. Name must be unique within an Org |
| `engine` | string | Yes | Cluster Application Engine |
| `values` | object | No | Values |
| `version` | string | No | Cluster Application Version |
| `replicas` | integer | No | The number of replicas, for standalone mode, the replicas is 1, for raftGroup mode, the default replicas is 3. |
| `cpu` | number (double) | No | CPU cores. |
| `memory` | number (double) | No | Memory, the unit is Gi. |
| `storage` | number (double) | No | Storage size, the unit is Gi. |
| `status` | string | No | status represents the actual status of the cluster in k8s, it is different from the state of the cluster in recycle bin, which means whether the cluster has been deleted by a stop opsRequest. |
| `state` | string | No | state represents whether the cluster has been deleted by a stop opsRequest, and therefore, whether it is in the recycle bin. It is differnt from the Status of the cluster undeleted. |
| `mode` | string | No | Cluster topology mode |
| `components` | [components](components.md) | No |  |
| `singleZone` | boolean | No | Use single availability zones |
| `availabilityZones` | string[] | No | Availability Zones |
| `backup` | [clusterBackup](clusterBackup.md) | No |  |
| `stoppedAt` | string (date-time) | No | StoppedAt is a timestamp representing the server time when this object was stopped and moved to the recycle bin.  |
| `createdAt` | string (date-time) | No | CreatedAt is a timestamp representing the server time when this object was created. |
| `expiredAt` | string (date-time) | No | ExpiredAt is a timestamp representing the server time when this object will be expired, and deleted automatically. |

