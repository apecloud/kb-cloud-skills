# GET /admin/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/groups

**Resource:** [dolphindb](../resources/dolphindb.md)
**DolphinDB ListGroups**
**Operation ID:** `dolphinDBListGroups`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Success |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

Array of [DolphinDBGroup](../schemas/Dolphin/DolphinDBGroup.md)

