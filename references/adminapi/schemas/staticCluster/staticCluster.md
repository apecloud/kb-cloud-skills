# staticCluster

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `components` | staticClusterComponent[] | No | Optional component overrides. Unknown, duplicate or other-engine components are rejected. Must be omitted when reusedClusterName is set; adding an environment does not resize an existing cluster. |
| `reusedClusterName` | string | No | Kubernetes name of an existing cluster to attach. Set together with reusedClusterNamespace. The existing cluster's actual resources are used, and component overrides are rejected. |
| `reusedClusterNamespace` | string | No | Namespace of the cluster named by reusedClusterName. Required when reusedClusterName is set. |

