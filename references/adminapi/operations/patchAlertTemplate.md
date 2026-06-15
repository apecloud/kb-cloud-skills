# PATCH /admin/v1/alertTemplates/{templateId}

**Resource:** [alertTemplate](../resources/alertTemplate.md)
**Update alert template**
**Operation ID:** `patchAlertTemplate`

partially update the alert receiver

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `templateId` | path | string | Yes | id of the alert tmpl configuration |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [alertTemplate](../schemas/alertTemplate/alertTemplate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned when project is deleted successfully. |
| 401 | (reference) |

**Success Response Schema:**

[alertTemplate](../schemas/alertTemplate/alertTemplate.md)

