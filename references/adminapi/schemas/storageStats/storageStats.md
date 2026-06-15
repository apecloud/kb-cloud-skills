# storageStats

StorageStats holds the resource stats of the volume, including bound PVC capacity, pod-used PVC capacity, and actual storage usage.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `requests` | number (double) | Yes | Requests is the total requested size of all PVCs that are already bound to volumes, unit is GiB |
| `podUsedCapacity` | number (double) | Yes | PodUsedCapacity is the total requested size of PVCs that are bound and currently used by pods, unit is GiB |
| `podUsedUsage` | number (double) | Yes | PodUsedUsage is the actual storage usage of PVCs that are used by pods, unit is GiB |

