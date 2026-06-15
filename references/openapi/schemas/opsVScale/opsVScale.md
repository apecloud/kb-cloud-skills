# opsVScale

OpsVScale is the payload to vertically scale a KubeBlocks cluster

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `component` | string | Yes | component type |
| `cpu` | string | No | number of cpu |
| `memory` | string | No | memory size |
| `classCode` | string | No | class code of the cluster |
| `schedule` | [taskSchedule](taskSchedule.md) | No |  |

