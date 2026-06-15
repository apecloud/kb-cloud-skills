# engineVersionCreate

EngineVersionRecord create option

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `engineName` | string | Yes | Name of the engine |
| `version` | string | Yes | Version of the engine |
| `kbVersionConstraint` | string | Yes | Version constraint for KB |
| `clusterChartUrl` | string | No | URL for the cluster chart |
| `chartUrl` | string | Yes | URL for the chart |
| `setValues` | string | No | Configuration values set for the engine |
| `chartsImage` | string | No | Image associated with the charts |
| `setImageRegistry` | boolean | No | Determines if the image registry is set |
| `serviceVersions` | string[] | Yes | Service versions supported by this engine version |

