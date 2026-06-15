# PATCH /admin/v1/sla/settings

**Resource:** [SLA](../resources/SLA.md)
**Update SLA settings**
**Operation ID:** `UpdateSLASettingsInEnv`

Update SLA settings in a environment

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | query | string | Yes | name of the environment |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [SLASettings](../schemas/SLASettings/SLASettings.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | SLA settings updated successfully |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

