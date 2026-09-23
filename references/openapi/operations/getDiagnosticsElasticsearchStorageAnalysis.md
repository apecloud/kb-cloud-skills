# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/elasticsearch/storageAnalysis

**Resource:** [diagnostics](../resources/diagnostics.md)
**Get Elasticsearch storage and index analysis**
**Operation ID:** `getDiagnosticsElasticsearchStorageAnalysis`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `node` | query | string | No |  |
| `index` | query | string | No |  |
| `sortBy` | query | elasticsearchIndexSortBy | No |  |
| `sortOrder` | query | elasticsearchSortOrder | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[elasticsearchStorageAnalysis](../schemas/elasticsearchStorageAnalysis/elasticsearchStorageAnalysis.md)

