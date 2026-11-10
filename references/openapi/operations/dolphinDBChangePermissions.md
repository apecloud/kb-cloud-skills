# PATCH /api/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/privileges/{subjectType}/{subjectName}

**Resource:** [dolphindb](../resources/dolphindb.md)
**DolphinDB ChangePermissions**
**Operation ID:** `dolphinDBChangePermissions`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `subjectType` | path | string | Yes |  |
| `subjectName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [DolphinDBPermissionChange](../schemas/Dolphin/DolphinDBPermissionChange.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Operation completed |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

