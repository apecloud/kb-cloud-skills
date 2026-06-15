# PATCH /api/v1/organizations/{orgName}/alerts/inhibits

**Resource:** [alertInhibit](../resources/alertInhibit.md)
**Patch alert inhibit**
**Operation ID:** `patchAlertInhibit`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |

## Request Body

**Content Types:** `application/json`

**Schema:** [alertInhibit](../schemas/alertInhibit/alertInhibit.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[alertInhibit](../schemas/alertInhibit/alertInhibit.md)

