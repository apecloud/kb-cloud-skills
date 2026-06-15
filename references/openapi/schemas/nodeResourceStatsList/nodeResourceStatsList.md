# nodeResourceStatsList

NodeResourceStatsList is a list of NodeResourceStats

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `items` | nodeResourceStats[] | Yes | Items is the list of NodeResourceStats objects in the list |
| `updatedAt` | string (date-time) | Yes | UpdatedAt is a timestamp representing the server time when this object was created. It is not guaranteed to be set in happens-before order across separate operations. Clients may not set this value. It is represented in RFC3339 form and is in UTC. Populated by the system. Read-only. Null for lists |

