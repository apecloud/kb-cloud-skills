# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/import/objects

**Resource:** [import](../resources/import.md)
**Query replication objects for import**
**Operation ID:** `queryImportObjects`

Enumerates replication objects (databases, schemas, tables, etc.) for the requested node. The metadata levels depend on the source engine (for example MySQL uses `database -> table`, PostgreSQL uses `schema -> table`).


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |

## Request Body

Connection configuration and current object tree position

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ImportQueryObjectsRequest](../schemas/Import/ImportQueryObjectsRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Object tree nodes retrieved successfully |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 501 | (reference) |

**Success Response Schema:**

[replicationObjectTree](../schemas/replicationObjectTree/replicationObjectTree.md)

