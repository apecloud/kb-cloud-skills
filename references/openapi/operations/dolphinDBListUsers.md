# GET /api/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/accounts

**Resource:** [dolphindb](../resources/dolphindb.md)
**DolphinDB ListUsers**
**Operation ID:** `dolphinDBListUsers`

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

Array of [DolphinDBUser](../schemas/Dolphin/DolphinDBUser.md)

