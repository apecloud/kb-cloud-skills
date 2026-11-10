# PATCH /api/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/password

**Resource:** [dolphindb](../resources/dolphindb.md)
**DolphinDB ChangePassword**
**Operation ID:** `dolphinDBChangePassword`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `accountName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [DolphinDBPasswordChange](../schemas/Dolphin/DolphinDBPasswordChange.md)

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

