# GET /api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/object-privileges/columns

**Resource:** [rdbms](../resources/rdbms.md)
**List exact column names for account object privileges**
**Operation ID:** `listAccountObjectPrivilegeColumns`

Read MySQL or PostgreSQL relation column names using the account management connection. No workbench datasource is required. Names are returned verbatim for column-level grants.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes |  |
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `accountName` | path | string | Yes |  |
| `objectType` | query | string | Yes | Object type, table/view; PostgreSQL also supports materializedView/foreignTable |
| `databaseName` | query | string | Yes |  |
| `objectName` | query | string | Yes |  |
| `schemaName` | query | string | No | Required for PostgreSQL; not accepted for MySQL |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Exact column names in catalog order; empty if no visible columns exist |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema** (inline):

Array

