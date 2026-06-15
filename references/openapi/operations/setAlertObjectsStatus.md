# PATCH /api/v1/organizations/{orgName}/alerts/objects

**Resource:** [alertObject](../resources/alertObject.md)
**Set alert objects status**
**Operation ID:** `setAlertObjectsStatus`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `status` | query | string | Yes |  |

## Request Body

**Content Types:** `application/json`

**Schema:** Array of [alertObject](../schemas/alertObject/alertObject.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[alertObjectList](../schemas/alertObjectList/alertObjectList.md)

