# POST /api/v1/organizations/{orgName}/clusters/batch

**Resource:** [cluster](../resources/cluster.md)
**Batch update clusters**
**Operation ID:** `batchUpdateClusters`

Update multiple clusters with the same update information (displayName and/or maintainceWindow) in a single request

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |

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

