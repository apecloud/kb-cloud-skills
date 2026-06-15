# GET /admin/v1/alertTemplates/{templateId}

**Resource:** [alertTemplate](../resources/alertTemplate.md)
**Get alert template**
**Operation ID:** `getAlertTemplate`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `templateId` | path | string | Yes | id of the alert tmpl configuration |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |

**Success Response Schema:**

[alertTemplate](../schemas/alertTemplate/alertTemplate.md)

