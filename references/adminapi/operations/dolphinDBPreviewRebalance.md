# GET /admin/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/rebalance/preview

**Resource:** [dolphindb](../resources/dolphindb.md)
**DolphinDB PreviewRebalance**
**Operation ID:** `dolphinDBPreviewRebalance`

Read-only preview recalculated on every request. Execution recomputes the actual plan. This operation does not scale the cluster or drain a node.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `offset` | query | integer | No |  |
| `limit` | query | integer | No |  |
| `updatedBeforeDays` | query | number | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Operation result |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[DolphinDBRebalancePreview](../schemas/Dolphin/DolphinDBRebalancePreview.md)

