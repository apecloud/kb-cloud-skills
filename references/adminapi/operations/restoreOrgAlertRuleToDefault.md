# POST /admin/v1/alerts/rules/reset

**Resource:** [alertRule](../resources/alertRule.md)
**Restore organization's alert rule configuration to defaults**
**Operation ID:** `restoreOrgAlertRuleToDefault`

Restores the alert rule configuration for a specific organization to the system default settings.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Alert rule configuration for the organization restored to defaults successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `message` | string | No |  |

