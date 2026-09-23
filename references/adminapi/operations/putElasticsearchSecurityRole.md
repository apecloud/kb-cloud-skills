# PUT /admin/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/roles/{roleName}

**Resource:** [elasticsearch](../resources/elasticsearch.md)
**Create or update Elasticsearch security role**
**Operation ID:** `putElasticsearchSecurityRole`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `roleName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ESSecurityRoleDescriptor](../schemas/ESSecurityRoleDescriptor/ESSecurityRoleDescriptor.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Create or update Elasticsearch security role successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

