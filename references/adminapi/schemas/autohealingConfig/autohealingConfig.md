# autohealingConfig

cluster instance autohealing process config

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enableAutoHealing` | boolean | Yes | Set to true to enable the auto-healing process, which automatically rebuilds instances when a node fails or is in maintenance mode. |
| `rebuildStartDelaySecondsWhenNodeFail` | integer (int32) | Yes | The number of seconds to wait before starting a rebuild when a node fails. |
| `rebuildStartDelaySecondsWhenInMaintenance` | integer (int32) | Yes | The number of seconds to wait before starting a rebuild when a node is in maintenance mode. |
| `minClusterRebuildIntervalSeconds` | integer (int32) | Yes | The minimum time in seconds between consecutive rebuild jobs for one cluster. |
| `rebuildConcurrencyPerNode` | integer (int32) | Yes | The maximum number of rebuild jobs that can run simultaneously for a single node. |
| `rebuildConcurrencyGlobally` | integer (int32) | Yes | The maximum number of rebuild jobs that can run simultaneously for the whole k8s cluster. |

