# GET /api/v1/data/hive/organizations/{orgName}/clusters/{clusterName}/accounts

**Resource:** [hive](../resources/hive.md)
**Get Hive accounts**
**Operation ID:** `getHiveAccounts`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The name of organization |
| `clusterName` | path | string | Yes | The name of cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Success |
| 204 | Returned when project is deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[accountList](../schemas/accountList/accountList.md)

