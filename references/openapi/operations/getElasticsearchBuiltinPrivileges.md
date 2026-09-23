# GET /api/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/privileges/builtin

**Resource:** [elasticsearch](../resources/elasticsearch.md)
**Get Elasticsearch builtin privileges**
**Operation ID:** `getElasticsearchBuiltinPrivileges`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Elasticsearch builtin privileges successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[ESBuiltinPrivileges](../schemas/ESBuiltinPrivileges/ESBuiltinPrivileges.md)

