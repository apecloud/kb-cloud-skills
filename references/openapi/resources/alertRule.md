# alertRule

Alert Rule APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v1/organizations/{orgName}/alerts/rules` | List alert rules | [View](../operations/listAlertRules.md) |
| POST | `/api/v1/organizations/{orgName}/alerts/rules` | Create alert rule | [View](../operations/createAlertRule.md) |
| GET | `/api/v1/organizations/{orgName}/alerts/rules/{alertName}` |  | [View](../operations/getAlertRule.md) |
| DELETE | `/api/v1/organizations/{orgName}/alerts/rules/{alertName}` | Delete alert rule | [View](../operations/deleteAlertRule.md) |
| PATCH | `/api/v1/organizations/{orgName}/alerts/rules/{alertName}` | Update alert rule | [View](../operations/updateAlertRule.md) |
| GET | `/api/v1/organizations/{orgName}/alerts/resource/{resourceType}/{resourceID}/rules` | List applicable alert rules for a resource | [View](../operations/listResourceAlertRules.md) |
| GET | `/api/v1/organizations/{orgName}/alerts/resource/{resourceType}/{resourceID}` | Get resource alert settings | [View](../operations/getResourceAlertDisabled.md) |
| PATCH | `/api/v1/organizations/{orgName}/alerts/resource/{resourceType}/{resourceID}` | Update resource alert settings | [View](../operations/setResourceAlertDisabled.md) |
| POST | `/api/v1/organizations/{orgName}/alerts/rules/config/restore` | Restore organization's alert rule configuration to defaults | [View](../operations/restoreOrgAlertRuleToDefault.md) |
