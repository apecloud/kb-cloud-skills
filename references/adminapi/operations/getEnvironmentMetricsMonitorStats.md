# GET /admin/v1/environments/{environmentName}/nodes/monitorStatus

**Resource:** [environment](../resources/environment.md)
**Get environment MetricsMonitorStats**
**Operation ID:** `getEnvironmentMetricsMonitorStats`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[jsonBody](../schemas/jsonBody/jsonBody.md)

