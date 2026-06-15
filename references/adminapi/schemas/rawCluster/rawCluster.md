# rawCluster

cluster info

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `kubernetesName` | string | No | the cluster name in k8s |
| `namespace` | string | No | the namespace of cluster |
| `replicas` | integer | No | the replicas of cluster |
| `storage` | number (double) | No | Storage size, the unit is Gi |
| `cpu` | number (double) | No | CPU cores. |
| `memory` | number (double) | No | Memory, the unit is Gi. |

