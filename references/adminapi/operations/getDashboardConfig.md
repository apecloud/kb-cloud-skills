# GET /admin/v1/dashboardConfigs/{key}

**Resource:** [dashboardConfig](../resources/dashboardConfig.md)
**Get dashboard configuration by key**
**Operation ID:** `getDashboardConfig`

Requires platform configuration read access. Missing keys return 200 with a null value.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Stored configuration or a null value for a missing key. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[dashboardConfig](../schemas/dashboardConfig/dashboardConfig.md)

