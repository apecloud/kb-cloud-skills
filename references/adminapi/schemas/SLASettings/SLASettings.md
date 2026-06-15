# SLASettings

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `environmentName` | string | No | The name of the environment. |
| `probeInterval` | string (duration) | No |  |
| `probeTimeout` | string (duration) | No |  |
| `enableProbeRetry` | boolean | No |  |
| `probeRetryCount` | integer | No |  |
| `probeRetryInterval` | string (duration) | No |  |
| `probeEngines` | string[] | No |  |
| `probePoolSize` | integer | No |  |
| `collectorBatchSize` | integer | No |  |
| `collectorMaxWaitTime` | string (duration) | No |  |
| `slaThreshold` | number | No | The SLA threshold value for the cluster. |

