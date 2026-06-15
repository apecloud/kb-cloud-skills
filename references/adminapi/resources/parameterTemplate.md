# parameterTemplate

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/parameterTemplates` | List parameter templates | [View](../operations/listParameterTemplates.md) |
| POST | `/admin/v1/parameterTemplates` | Create parameter template | [View](../operations/createParameterTemplate.md) |
| GET | `/admin/v1/parameterTemplate/{parameterTemplateName}` | Get parameter template details | [View](../operations/readParameterTemplate.md) |
| DELETE | `/admin/v1/parameterTemplate/{parameterTemplateName}` | Delete parameter template | [View](../operations/deleteParameterTemplate.md) |
| PATCH | `/admin/v1/parameterTemplate/{parameterTemplateName}` | Update parameter template | [View](../operations/patchParameterTemplate.md) |
| GET | `/admin/v1/parameterTemplate/{parameterTemplateName}/diff` | Get parameter template diff against default template | [View](../operations/readParameterTemplateDiff.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/parameterTemplate` | Get cluster parameter template | [View](../operations/getClusterParameterTemplate.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/parameterTemplate` | Export parameter template from cluster | [View](../operations/exportParameterTemplateFromCluster.md) |
| PATCH | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/parameterTemplate` | Update cluster parameter template | [View](../operations/updateClusterParameterTemplate.md) |
