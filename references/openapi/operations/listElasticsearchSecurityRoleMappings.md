# GET /api/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/role-mappings

**Resource:** [elasticsearch](../resources/elasticsearch.md)
**List Elasticsearch security role mappings**
**Operation ID:** `listElasticsearchSecurityRoleMappings`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Elasticsearch security role mappings successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[ESSecurityRoleMappings](../schemas/ESSecurityRoleMappings/ESSecurityRoleMappings.md)

