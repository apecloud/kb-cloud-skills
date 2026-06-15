# DELETE /api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections/{col}/indexes/{indexName}

**Resource:** [dms](../resources/dms.md)
**drop MongoDB collection index**
**Operation ID:** `mongoDropIndex`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `id` | path | string | Yes |  |
| `db` | path | string | Yes |  |
| `col` | path | string | Yes |  |
| `indexName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | index dropped |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

