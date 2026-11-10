# GET /api/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/privileges/{subjectType}/{subjectName}

**Resource:** [dolphindb](../resources/dolphindb.md)
**DolphinDB GetPermissions**
**Operation ID:** `dolphinDBGetPermissions`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `subjectType` | path | string | Yes |  |
| `subjectName` | path | string | Yes |  |

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

[DolphinDBPermissionSnapshot](../schemas/Dolphin/DolphinDBPermissionSnapshot.md)

