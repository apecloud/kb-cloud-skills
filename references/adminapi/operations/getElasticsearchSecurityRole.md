# GET /admin/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/roles/{roleName}

**Resource:** [elasticsearch](../resources/elasticsearch.md)
**Get Elasticsearch security role**
**Operation ID:** `getElasticsearchSecurityRole`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `roleName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Elasticsearch security role successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[ESSecurityRoleDescriptor](../schemas/ESSecurityRoleDescriptor/ESSecurityRoleDescriptor.md)

