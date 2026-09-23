# elasticsearch

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts` | List Elasticsearch security users | [View](../operations/listElasticsearchSecurityUsers.md) |
| GET | `/admin/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/{username}` | Get Elasticsearch security user | [View](../operations/getElasticsearchSecurityUser.md) |
| PUT | `/admin/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/{username}` | Create or update Elasticsearch security user | [View](../operations/putElasticsearchSecurityUser.md) |
| DELETE | `/admin/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/{username}` | Delete Elasticsearch security user | [View](../operations/deleteElasticsearchSecurityUser.md) |
| PATCH | `/admin/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/{username}` | Change Elasticsearch account password | [View](../operations/changeElasticsearchSecurityUserPassword.md) |
| PATCH | `/admin/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/{username}/lock` | Lock Elasticsearch account | [View](../operations/lockElasticsearchSecurityUser.md) |
| PATCH | `/admin/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/{username}/unlock` | Unlock Elasticsearch account | [View](../operations/unlockElasticsearchSecurityUser.md) |
| GET | `/admin/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/roles` | List Elasticsearch security roles | [View](../operations/listElasticsearchSecurityRoles.md) |
| GET | `/admin/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/roles/{roleName}` | Get Elasticsearch security role | [View](../operations/getElasticsearchSecurityRole.md) |
| PUT | `/admin/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/roles/{roleName}` | Create or update Elasticsearch security role | [View](../operations/putElasticsearchSecurityRole.md) |
| DELETE | `/admin/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/roles/{roleName}` | Delete Elasticsearch security role | [View](../operations/deleteElasticsearchSecurityRole.md) |
| GET | `/admin/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/role-mappings` | List Elasticsearch security role mappings | [View](../operations/listElasticsearchSecurityRoleMappings.md) |
| GET | `/admin/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/role-mappings/{mappingName}` | Get Elasticsearch security role mapping | [View](../operations/getElasticsearchSecurityRoleMapping.md) |
| PUT | `/admin/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/role-mappings/{mappingName}` | Create or update Elasticsearch security role mapping | [View](../operations/putElasticsearchSecurityRoleMapping.md) |
| DELETE | `/admin/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/role-mappings/{mappingName}` | Delete Elasticsearch security role mapping | [View](../operations/deleteElasticsearchSecurityRoleMapping.md) |
| GET | `/admin/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/privileges/builtin` | Get Elasticsearch builtin privileges | [View](../operations/getElasticsearchBuiltinPrivileges.md) |
