# reconfigureCreate

ReconfigureCreate is the payload to reconfigure a KubeBlocks cluster

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `component` | string | Yes | component type |
| `configFileName` | string | No | config file name |
| `parameters` | object | No | Specify parameters list to be updated |
| `rawContent` | string | No | The raw content of the configuration file |
| `schedule` | [taskSchedule](taskSchedule.md) | No |  |

