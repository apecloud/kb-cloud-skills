# GET /api/v1/organizations/{orgName}/alerts/inhibits/{inhibitId}

**Resource:** [alertInhibit](../resources/alertInhibit.md)
**Get alert inhibit**
**Operation ID:** `getAlertInhibit`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `inhibitId` | path | string | Yes | inhibit id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[alertInhibit](../schemas/alertInhibit/alertInhibit.md)

