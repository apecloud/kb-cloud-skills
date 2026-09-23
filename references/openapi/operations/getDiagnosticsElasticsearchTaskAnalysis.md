# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/elasticsearch/taskAnalysis

**Resource:** [diagnostics](../resources/diagnostics.md)
**Get Elasticsearch task and hot-thread analysis**
**Operation ID:** `getDiagnosticsElasticsearchTaskAnalysis`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `type` | query | elasticsearchHotThreadsType | No |  |
| `node` | query | string | No |  |
| `taskLimit` | query | integer | No |  |
| `threads` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[elasticsearchTaskAnalysis](../schemas/elasticsearchTaskAnalysis/elasticsearchTaskAnalysis.md)

