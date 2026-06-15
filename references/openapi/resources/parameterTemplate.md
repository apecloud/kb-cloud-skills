# parameterTemplate

Parameter Template APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v1/organizations/{orgName}/parameterTemplates` | List parameter templates in an Org | [View](../operations/listParameterTemplates.md) |
| POST | `/api/v1/organizations/{orgName}/parameterTemplates` | Create parameter template | [View](../operations/createParameterTemplate.md) |
| GET | `/api/v1/organizations/{orgName}/parameterTemplate/{parameterTemplateName}` | Get parameter template details | [View](../operations/readParameterTemplate.md) |
| DELETE | `/api/v1/organizations/{orgName}/parameterTemplate/{parameterTemplateName}` | Delete parameter template | [View](../operations/deleteParameterTemplate.md) |
| PATCH | `/api/v1/organizations/{orgName}/parameterTemplate/{parameterTemplateName}` | Update parameter template | [View](../operations/patchParameterTemplate.md) |
| GET | `/api/v1/organizations/{orgName}/parameterTemplate/{parameterTemplateName}/diff` | Get parameter template diff against default template | [View](../operations/readParameterTemplateDiff.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/parameterTemplate` | Get cluster parameter template | [View](../operations/getClusterParameterTemplate.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/parameterTemplate` | Export parameter template from cluster | [View](../operations/exportParameterTemplateFromCluster.md) |
| PATCH | `/api/v1/organizations/{orgName}/clusters/{clusterName}/parameterTemplate` | Update cluster parameter template | [View](../operations/updateClusterParameterTemplate.md) |
