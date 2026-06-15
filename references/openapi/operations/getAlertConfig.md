# GET /api/v1/organizations/{orgName}/alerts/config

**Resource:** [alertConfig](../resources/alertConfig.md)
**Get alert config**
**Operation ID:** `getAlertConfig`

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

[alertConfig](../schemas/alertConfig/alertConfig.md)

