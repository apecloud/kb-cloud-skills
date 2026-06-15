# DELETE /api/v1/organizations/{orgName}/alerts/inhibits/{inhibitId}

**Resource:** [alertInhibit](../resources/alertInhibit.md)
**Delete alert inhibit**
**Operation ID:** `deleteAlertInhibit`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `inhibitId` | path | string | Yes | inhibit id |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when project is deleted successfully. |
| 403 | (reference) |
| 404 | (reference) |

