# GET /admin/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/roles

**Resource:** [elasticsearch](../resources/elasticsearch.md)
**List Elasticsearch security roles**
**Operation ID:** `listElasticsearchSecurityRoles`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Elasticsearch security roles successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[ESSecurityRoles](../schemas/ESSecurityRoles/ESSecurityRoles.md)

