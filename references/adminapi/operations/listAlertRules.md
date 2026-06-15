# GET /admin/v1/alerts/rules

**Resource:** [alertRule](../resources/alertRule.md)
**List alert rules**
**Operation ID:** `listAlertRules`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `disabled` | query | boolean | No | disabled status |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[alertRuleList](../schemas/alertRuleList/alertRuleList.md)

