# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections/{col}/schema

**Resource:** [dms](../resources/dms.md)
**analyze MongoDB collection schema from sample documents**
**Operation ID:** `mongoAnalyzeSchema`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `id` | path | string | Yes |  |
| `db` | path | string | Yes |  |
| `col` | path | string | Yes |  |
| `sample` | query | integer (int64) | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[MongoSchemaAnalysis](../schemas/Mongo/MongoSchemaAnalysis.md)

