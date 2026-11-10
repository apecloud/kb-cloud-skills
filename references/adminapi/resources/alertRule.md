# alertRule

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/organizations/{orgName}/alerts/resource/{resourceType}/{resourceID}/rules` | List applicable alert rules for a resource | [View](../operations/listResourceAlertRules.md) |
| GET | `/admin/v1/organizations/{orgName}/alerts/resource/{resourceType}/{resourceID}` | Get resource alert settings | [View](../operations/getResourceAlertDisabled.md) |
| PATCH | `/admin/v1/organizations/{orgName}/alerts/resource/{resourceType}/{resourceID}` | Update resource alert settings | [View](../operations/setResourceAlertDisabled.md) |
| GET | `/admin/v1/alerts/rules` | List alert rules | [View](../operations/listAlertRules.md) |
| POST | `/admin/v1/alerts/rules` | Create alert rule | [View](../operations/createAlertRule.md) |
| PATCH | `/admin/v1/alerts/rules` |  | [View](../operations/updateAlertRule.md) |
| GET | `/admin/v1/alerts/rules/{alertName}` | Get alert rule | [View](../operations/getAlertRule.md) |
| DELETE | `/admin/v1/alerts/rules/{alertName}` | Delete alert rule | [View](../operations/deleteAlertRule.md) |
| POST | `/admin/v1/alerts/rules/reset` | Restore organization's alert rule configuration to defaults | [View](../operations/restoreOrgAlertRuleToDefault.md) |
