# pod

Single pod information for environment module

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | Pod name |
| `namespace` | string | No | Pod namespace |
| `nodeName` | string | No | Node name where pod is running |
| `status` | string | No | Pod status |
| `phase` | string | No | Pod phase |
| `ip` | string | No | Pod IP address |
| `creationTimestamp` | string (date-time) | No | Pod creation time |
| `resources` | [podResources](podResources.md) | No |  |
| `ownerReferences` | podOwnerReference[] | No |  |
| `containers` | containerInfo[] | No |  |
| `conditions` | podCondition[] | No |  |

