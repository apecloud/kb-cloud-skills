# PATCH /api/v1/organizations/{orgName}/alerts/config

**Resource:** [alertConfig](../resources/alertConfig.md)
**Set alert config**
**Operation ID:** `setAlertConfig`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |

## Request Body

**Content Types:** `application/json`

**Schema:** [alertConfig](../schemas/alertConfig/alertConfig.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[alertConfig](../schemas/alertConfig/alertConfig.md)

