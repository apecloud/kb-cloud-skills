# POST /api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/databases

**Resource:** [database](../resources/database.md)
**Create cluster database**
**Operation ID:** `createDatabase`

create a database in cluster

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | name of the engine |
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [database](../schemas/database/database.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when database is created successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

