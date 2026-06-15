# recycleBinClusterListItem

information of kubeblocks cluster in recycle bin

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cloudProvider` | string | Yes | Cloud Provider |
| `cloudRegion` | string | No | Cloud Provider |
| `availabilityZones` | string[] | No | Availability Zones |
| `displayName` | string | No | Display name of cluster. |
| `engine` | string | Yes | Cluster Application Engine |
| `mode` | string | No | Cluster topology mode |
| `environmentName` | string | Yes | Environment Name |
| `id` | string | Yes | Cluster Recycle Bin ID |
| `clusterId` | string | No | Cluster ID |
| `name` | string | Yes | Name of cluster. Name must be unique within an Org |
| `version` | string | Yes | Cluster Application Version |
| `classCode` | string | No | Cluster main component classCode |
| `storage` | string | No | Cluster main component storage |
| `orgName` | string | No | Name of the Org |
| `state` | string | Yes | state represents whether the cluster has been deleted by a stop opsRequest, and therefore, whether it is in the recycle bin. It is differnt from the Status.Phase of the cluster in k8s. |
| `stoppedAt` | string (date-time) | Yes | StoppedAt is a timestamp representing the server time when this object was stopped and moved to the recycle bin.  |
| `createdAt` | string (date-time) | No | CreatedAt is a timestamp representing the server time when this object was created. |
| `expiredAt` | string (date-time) | No | ExpiredAt is a timestamp representing the server time when this object will be expired, and deleted automatically. |

