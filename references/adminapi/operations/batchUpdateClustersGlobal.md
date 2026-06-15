# POST /admin/v1/clusters/batch

**Resource:** [cluster](../resources/cluster.md)
**Batch update clusters**
**Operation ID:** `batchUpdateClustersGlobal`

Update multiple clusters with the same update information (displayName and/or maintainceWindow) in a single request

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [clusterBatchUpdate](../schemas/clusterBatchUpdate/clusterBatchUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when clusters are updated successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

