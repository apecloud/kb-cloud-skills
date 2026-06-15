# storageClassNodeStats

storageClassNodeStats is a storage class node stats.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `nodeName` | string | Yes | the name of the node |
| `nodeStatus` | string | Yes | the status of the node |
| `requests` | number (double) | Yes | the total requests size of all PVCs on the node |
| `usage` | number (double) | Yes | the actual disk usage of hostpath on the node |
| `capacity` | number (double) | Yes | the capacity of hostpath on the node |
| `pvcCount` | integer | Yes | the number of PVCs on the node |

