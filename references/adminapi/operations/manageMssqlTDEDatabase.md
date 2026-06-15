# PATCH /admin/v1/data/mssql/organizations/{orgName}/clusters/{clusterName}/tde

**Resource:** [mssql](../resources/mssql.md)
**batch modify database tde status**
**Operation ID:** `manageMssqlTDEDatabase`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the organization |
| `clusterName` | path | string | Yes | name of the cluster |

## Request Body

**Content Types:** `application/json`

**Schema:** [dbTDERequest](../schemas/dbTDERequest/dbTDERequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Enable mssql database in tde successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

