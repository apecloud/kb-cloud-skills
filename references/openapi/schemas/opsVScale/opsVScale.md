# opsVScale

OpsVScale is the payload to vertically scale a KubeBlocks cluster

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `component` | string | Yes | component type |
| `cpu` | string | No | number of cpu |
| `memory` | string | No | memory size |
| `classCode` | string | No | Class code for component-level vertical scaling. |
| `schedule` | [taskSchedule](taskSchedule.md) | No |  |

