# GET /admin/v1/alerts/objects

**Resource:** [alertObject](../resources/alertObject.md)
**List alert objects**
**Operation ID:** `listAlertObjects`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | page number |
| `pageSize` | query | integer | No | page size |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[alertObjectList](../schemas/alertObjectList/alertObjectList.md)

