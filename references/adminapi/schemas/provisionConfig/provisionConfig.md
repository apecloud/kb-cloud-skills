# provisionConfig

Configuration to provision infrastructure for this environment

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `register` | [register](register.md) | Yes |  |
| `component` | [component](component.md) | Yes |  |
| `nodePool` | [nodePool](nodePool.md) | No |  |
| `storage` | [storageConfig](storageConfig.md) | No |  |
| `victoriaMetrics` | [staticCluster](staticCluster.md) | No |  |
| `victoriaLogs` | [victoriaLogsConfig](victoriaLogsConfig.md) | No |  |
| `modules` | environmentModule[] | No | option modules of environment |

