# GET /api/v1/organizations/{orgName}/alerts/objects

**Resource:** [alertObject](../resources/alertObject.md)
**List alert objects**
**Operation ID:** `listAlertObjects`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
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

