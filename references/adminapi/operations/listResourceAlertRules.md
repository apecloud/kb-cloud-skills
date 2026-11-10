# GET /admin/v1/organizations/{orgName}/alerts/resource/{resourceType}/{resourceID}/rules

**Resource:** [alertRule](../resources/alertRule.md)
**List applicable alert rules for a resource**
**Operation ID:** `listResourceAlertRules`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `resourceType` | path | alertResourceType | Yes | resourceType |
| `resourceID` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[alertRuleList](../schemas/alertRuleList/alertRuleList.md)

