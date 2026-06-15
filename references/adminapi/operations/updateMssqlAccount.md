# PATCH /admin/v1/data/mssql/organizations/{orgName}/clusters/{clusterName}/accounts

**Resource:** [mssql](../resources/mssql.md)
**update mssql account compatible with windows account**
**Operation ID:** `updateMssqlAccount`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the organization |
| `clusterName` | path | string | Yes | name of the cluster |

## Request Body

**Content Types:** `application/json`

**Schema:** [account](../schemas/account/account.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Update mssql account successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

