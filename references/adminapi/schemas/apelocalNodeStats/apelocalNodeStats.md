# apelocalNodeStats

apelocal-specific capacity measurements for one node. Missing measurements are omitted.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `allocationResourceID` | string | No | Node-local backing allocation resource identity, used to deduplicate SC aliases. |
| `physicalResourceID` | string | No | Node-local observed filesystem identity, used to deduplicate shared physical capacity. |
| `physicalCapacity` | number (double) | No | Observed filesystem capacity in GiB; omitted when the backing filesystem cannot be identified completely. |
| `physicalUsage` | number (double) | No | Observed filesystem used bytes in GiB, including other data on the same filesystem. |
| `allocatableCapacity` | number (double) | No | CSI total allocatable capacity in GiB; omitted for unlimited capacity. |
| `availableCapacity` | number (double) | No | CSI remaining allocatable capacity in GiB; omitted for unlimited capacity. |
| `allocatedCapacity` | number (double) | No | Capacity accounted for by CSI in GiB, including shared definitions; omitted when it cannot be determined exactly. |
| `maximumVolumeSize` | number (double) | No | Largest volume CSI can allocate on this node in GiB. |

