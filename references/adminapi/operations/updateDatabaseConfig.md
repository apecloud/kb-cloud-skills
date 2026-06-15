# PATCH /admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/databases/{databaseName}

**Resource:** [database](../resources/database.md)
**update database config**
**Operation ID:** `updateDatabaseConfig`

update a database config in cluster

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | name of the engine |
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |
| `databaseName` | path | string | Yes | name of database |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when project is deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

