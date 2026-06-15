# GET /api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/databases

**Resource:** [database](../resources/database.md)
**List cluster databases**
**Operation ID:** `listDatabases`

list databases for rdbms engine cluster

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | name of the engine |
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[databaseList](../schemas/databaseList/databaseList.md)

