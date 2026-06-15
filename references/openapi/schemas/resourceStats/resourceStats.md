# resourceStats

ResourceStats holds the requests, limits, and available stats for a resource.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `allocatable` | number (double) | No | The amount of CPU or Memory resources that are available on the node. Unit is GiB for memory and Cores for CPU. |
| `limits` | number (double) | No | The maximum number of CPU or Memory resources pods are allowed to use on the node.  Unit is GiB for memory and Cores for CPU |
| `requests` | number (double) | No | The number of CPU or Memory resources requested by pods running on the node. Unit is GiB for memory and Cores for CPU. |
| `usage` | number (double) | Yes | The amount of CPU or Memory resources that are already used on the node. Unit is GiB for memory and Cores for CPU. |
| `capacity` | number (double) | No | The total amount of physical resources available on the node. Unit is GiB for memory and Cores for CPU. |

