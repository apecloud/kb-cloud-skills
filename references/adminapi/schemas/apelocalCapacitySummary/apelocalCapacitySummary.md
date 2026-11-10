# apelocalCapacitySummary

Deduplicated apelocal statistics. Does not include other storage drivers. Missing measurements are omitted, never treated as zero.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `observed` | [apelocalCapacityObservations](apelocalCapacityObservations.md) | No |  |
| `capacityMode` | [apelocalCapacitySummaryMode](apelocalCapacitySummaryMode.md) | No |  |
| `complete` | boolean | No | Whether all required measurements for the selected capacity mode are present. |
| `nodeCount` | integer | No |  |
| `unavailableNodeCount` | integer | No |  |
| `physicalCapacity` | number (double) | No | Physical capacity in GiB, deduplicated by backing filesystem. |
| `physicalUsage` | number (double) | No | Physical filesystem usage in GiB, including other files. |
| `allocatableCapacity` | number (double) | No | Logical total in GiB; omitted for unlimited or conflicting quotas. |
| `allocatedCapacity` | number (double) | No | CSI allocated capacity in GiB, deduplicated by backing allocation resource. |
| `availableCapacity` | number (double) | No | Remaining logical capacity in GiB on ready schedulable nodes only. |

