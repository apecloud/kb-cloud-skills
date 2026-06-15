# DELETE /api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/databases/{databaseName}

**Resource:** [database](../resources/database.md)
**Delete cluster database**
**Operation ID:** `deleteDatabase`

delete a database in cluster

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | name of the engine |
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |
| `databaseName` | path | string | Yes | name of database |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when project is deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

