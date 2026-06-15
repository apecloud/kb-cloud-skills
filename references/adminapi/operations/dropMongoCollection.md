# DELETE /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections/{col}

**Resource:** [dms](../resources/dms.md)
**drop a MongoDB collection or view**
**Operation ID:** `dropMongoCollection`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `id` | path | string | Yes | id of the datasource |
| `db` | path | string | Yes | database name |
| `col` | path | string | Yes | collection or view name |

## Responses

| Status | Description |
|--------|-------------|
| 204 | collection or view dropped |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

