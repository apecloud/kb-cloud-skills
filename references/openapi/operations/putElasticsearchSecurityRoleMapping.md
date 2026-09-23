# PUT /api/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/role-mappings/{mappingName}

**Resource:** [elasticsearch](../resources/elasticsearch.md)
**Create or update Elasticsearch security role mapping**
**Operation ID:** `putElasticsearchSecurityRoleMapping`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `mappingName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ESSecurityRoleMapping](../schemas/ESSecurityRoleMapping/ESSecurityRoleMapping.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Create or update Elasticsearch security role mapping successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

