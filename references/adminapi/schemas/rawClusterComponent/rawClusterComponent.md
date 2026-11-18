# rawClusterComponent

Actual resources of one component in a discovered cluster.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `component` | string | No | Component name, such as vm-storage or vlselect. |
| `replicas` | integer | No | the replicas of this component |
| `storage` | number (double) | No | Storage size, the unit is Gi |
| `cpu` | number (double) | No | CPU cores. |
| `memory` | number (double) | No | Memory, the unit is Gi. |
| `classCode` | string | No | Class code recorded for this component. |

