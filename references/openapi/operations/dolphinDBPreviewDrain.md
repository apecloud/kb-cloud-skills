# POST /api/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/rebalance/drain-preview

**Resource:** [dolphindb](../resources/dolphindb.md)
**Preview DolphinDB data node evacuation**
**Operation ID:** `dolphinDBPreviewDrain`

Read-only evacuation preview computed by an embedded DMS planner from native controller metadata. No addon planner or module upgrade is required. Does not evacuate data, reserve a plan, or remove a node. Existing HorizontalScaling/memberLeave independently checks current state and executes; capacity is not inferred from chunk size.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `offset` | query | integer | No |  |
| `limit` | query | integer | No |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [DolphinDBDrainRequest](../schemas/Dolphin/DolphinDBDrainRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Observed evacuation plan |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[DolphinDBDrainPreview](../schemas/Dolphin/DolphinDBDrainPreview.md)

