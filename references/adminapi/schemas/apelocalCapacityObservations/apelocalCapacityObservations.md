# apelocalCapacityObservations

Known-node aggregates after resource deduplication. Capacity values are in GiB and ratios are percentages using only nodes with both inputs. Independent measurements can cover different nodes. Quota, remaining quota and allocation percentage objects are omitted for unlimited or conflicting policies. Remaining quota covers only ready schedulable nodes. Physical remaining is capacity minus usage from nodes with both measurements and usage not exceeding capacity; it is not a guaranteed writable or schedulable quota. Existing summary totals remain omitted when incomplete.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `physicalCapacity` | [apelocalCapacityObservation](apelocalCapacityObservation.md) | No |  |
| `physicalUsage` | [apelocalCapacityObservation](apelocalCapacityObservation.md) | No |  |
| `physicalRemaining` | [apelocalCapacityObservation](apelocalCapacityObservation.md) | No |  |
| `allocatedCapacity` | [apelocalCapacityObservation](apelocalCapacityObservation.md) | No |  |
| `allocatableCapacity` | [apelocalCapacityObservation](apelocalCapacityObservation.md) | No |  |
| `availableCapacity` | [apelocalCapacityObservation](apelocalCapacityObservation.md) | No |  |
| `physicalUsagePercent` | [apelocalCapacityObservation](apelocalCapacityObservation.md) | No |  |
| `allocationPercent` | [apelocalCapacityObservation](apelocalCapacityObservation.md) | No |  |

