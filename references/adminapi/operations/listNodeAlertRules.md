# GET /admin/v1/environments/{environmentName}/nodes/{nodeName}/alert/rules

**Resource:** [nodeAlert](../resources/nodeAlert.md)
**List node metric and NodeDown event alert rules**
**Operation ID:** `listNodeAlertRules`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes |  |
| `nodeName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Success |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[alertRuleList](../schemas/alertRuleList/alertRuleList.md)

