# nodeAlert

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/environments/{environmentName}/nodes/{nodeName}/alert/settings` | Get alert settings for a node in an environment | [View](../operations/getNodeAlertSettings.md) |
| PATCH | `/admin/v1/environments/{environmentName}/nodes/{nodeName}/alert/settings` | Update supplied node alert settings; omitted fields are preserved | [View](../operations/patchNodeAlertSettings.md) |
| GET | `/admin/v1/environments/{environmentName}/nodes/{nodeName}/alert/rules` | List node metric and NodeDown event alert rules | [View](../operations/listNodeAlertRules.md) |
