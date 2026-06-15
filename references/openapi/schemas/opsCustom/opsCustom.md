# opsCustom

OpsCustom is the payload to create a custom KubeBlocks OpsRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `compName` | string | Yes | component name |
| `opsType` | string | Yes | ops definition name. |
| `dependentOnOps` | string[] | No | ops definition name. |
| `params` | opsParameter[] | No | custom ops parameters |
| `schedule` | [taskSchedule](taskSchedule.md) | No |  |

