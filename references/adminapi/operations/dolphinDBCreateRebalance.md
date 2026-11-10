# POST /admin/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/rebalance/operations

**Resource:** [dolphindb](../resources/dolphindb.md)
**DolphinDB CreateRebalance**
**Operation ID:** `dolphinDBCreateRebalance`

Submit the built-in dolphindb-rebalance Custom Ops through the platform scheduler. Returns the unified taskId; use platform task APIs for history and status. A timeout or cancellation does not cancel native migrations. Do not automatically resubmit a timed-out request.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [DolphinDBRebalanceRequest](../schemas/Dolphin/DolphinDBRebalanceRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 202 | Operation result |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

