# apelocalStorageClassStats

apelocal-specific StorageClass capacity policy and measurements.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `summary` | [apelocalCapacitySummary](apelocalCapacitySummary.md) | No |  |
| `definitionName` | string | No | Resolved apelocal HostPathDefinition name. |
| `backendType` | string | No | apelocal storage backend (HostDir, RawDisk or RawDiskGroup). |
| `capacityMode` | [apelocalCapacityMode](apelocalCapacityMode.md) | No |  |
| `capacityMultiplier` | number (double) | No | Capacity multiplier (1.2 means 120 percent). |
| `fixedCapacity` | number (double) | No | Configured fixed capacity per node in GiB. |
| `metricsAvailable` | boolean | No | Whether the metrics query succeeded; individual measurements can still be absent. |

