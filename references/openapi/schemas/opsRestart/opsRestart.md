# opsRestart

OpsRestart is the payload to restart a KubeBlocks cluster

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `component` | string | Yes | component type |
| `force` | boolean | No | whether to force restart the component |
| `preConditionDeadlineSeconds` | integer | No | Specifies the maximum time in seconds that the OpsRequest will wait for its pre-conditions to be met before it aborts the operation |
| `schedule` | [taskSchedule](taskSchedule.md) | No |  |

