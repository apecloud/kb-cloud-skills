# GET /admin/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/privileges/capabilities

**Resource:** [dolphindb](../resources/dolphindb.md)
**DolphinDB GetCapabilities**
**Operation ID:** `dolphinDBGetCapabilities`

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

[DolphinDBCapabilities](../schemas/Dolphin/DolphinDBCapabilities.md)

