# GET /admin/v1/sla/settings

**Resource:** [SLA](../resources/SLA.md)
**Get SLA settings**
**Operation ID:** `GetSLASettingsInEnv`

Get SLA settings in a environment

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | query | string | Yes | name of the environment |

## Responses

| Status | Description |
|--------|-------------|
| 200 | SLA settings retrieved successfully |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[SLASettings](../schemas/SLASettings/SLASettings.md)

