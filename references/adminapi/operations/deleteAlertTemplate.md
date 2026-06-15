# DELETE /admin/v1/alertTemplates/{templateId}

**Resource:** [alertTemplate](../resources/alertTemplate.md)
**Delete alert template**
**Operation ID:** `deleteAlertTemplate`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `templateId` | path | string | Yes | id of the alert tmpl configuration |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when project is deleted successfully. |
| 403 | (reference) |
| 404 | (reference) |

