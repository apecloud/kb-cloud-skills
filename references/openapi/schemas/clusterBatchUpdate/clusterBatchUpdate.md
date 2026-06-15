# clusterBatchUpdate

ClusterBatchUpdate is the payload for batch updating multiple clusters with the same update information

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `clusterIDs` | string[] | Yes | List of cluster ID to update |
| `update` | [clusterBatchUpdateData](clusterBatchUpdateData.md) | Yes |  |

