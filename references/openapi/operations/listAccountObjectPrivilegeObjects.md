# GET /api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/object-privileges/objects

**Resource:** [rdbms](../resources/rdbms.md)
**Discover existing native privilege objects with stable routine identities**
**Operation ID:** `listAccountObjectPrivilegeObjects`

Lists existing objects of one supported kind. Pagination is not a fixed snapshot. PostgreSQL requires a connection database; schema-contained kinds require schemaName. MySQL global/database listing omits databaseName; other kinds require it.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes |  |
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `accountName` | path | string | Yes |  |
| `objectType` | query | string | Yes |  |
| `databaseName` | query | string | No |  |
| `schemaName` | query | string | No |  |
| `offset` | query | integer (int64) | No |  |
| `limit` | query | integer (int64) | No |  |
| `catalogName` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Native privilege snapshot |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[ObjectPrivilegeObjectList](../schemas/Object/ObjectPrivilegeObjectList.md)

