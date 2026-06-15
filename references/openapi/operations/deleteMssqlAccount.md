# DELETE /api/v1/data/mssql/organizations/{orgName}/clusters/{clusterName}/accounts

**Resource:** [mssql](../resources/mssql.md)
**delete mssql account compatible with windows account**
**Operation ID:** `deleteMssqlAccount`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the organization |
| `clusterName` | path | string | Yes | name of the cluster |
| `account` | query | string | Yes | name of the account |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when project is deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

