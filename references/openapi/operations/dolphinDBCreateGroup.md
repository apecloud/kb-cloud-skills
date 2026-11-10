# POST /api/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/groups

**Resource:** [dolphindb](../resources/dolphindb.md)
**DolphinDB CreateGroup**
**Operation ID:** `dolphinDBCreateGroup`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [DolphinDBGroupCreate](../schemas/Dolphin/DolphinDBGroupCreate.md)

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

