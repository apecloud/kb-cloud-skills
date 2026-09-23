# GET /api/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/role-mappings/{mappingName}

**Resource:** [elasticsearch](../resources/elasticsearch.md)
**Get Elasticsearch security role mapping**
**Operation ID:** `getElasticsearchSecurityRoleMapping`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `mappingName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Elasticsearch security role mapping successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[ESSecurityRoleMapping](../schemas/ESSecurityRoleMapping/ESSecurityRoleMapping.md)

