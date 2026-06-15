# DELETE /admin/v1/classes

**Resource:** [class](../resources/class.md)
**Delete class**
**Operation ID:** `deleteClass`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `code` | query | string | Yes | code |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when project is deleted successfully. |
| 403 | (reference) |
| 404 | (reference) |

