# GET /admin/v1/platformParameters/{platformParameterName}

**Resource:** [platformParameter](../resources/platformParameter.md)
**get platformParameter by name**
**Operation ID:** `getPlatformParameter`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `platformParameterName` | path | string | Yes | name of the platformParameter |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[platformParameter](../schemas/platformParameter/platformParameter.md)

