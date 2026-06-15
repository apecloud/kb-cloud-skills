# GET /api/v1/organizations/{orgName}/alerts/inhibits

**Resource:** [alertInhibit](../resources/alertInhibit.md)
**List alert inhibits**
**Operation ID:** `listAlertInhibits`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[alertInhibitList](../schemas/alertInhibitList/alertInhibitList.md)

