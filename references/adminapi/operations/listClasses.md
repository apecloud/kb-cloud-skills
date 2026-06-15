# GET /admin/v1/classes

**Resource:** [class](../resources/class.md)
**List classes**
**Operation ID:** `listClasses`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | query | string | No | filter by engine name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [class](../schemas/class/class.md)

