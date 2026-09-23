# DELETE /admin/v1/dashboardConfigs/{key}

**Resource:** [dashboardConfig](../resources/dashboardConfig.md)
**Delete dashboard configuration by key**
**Operation ID:** `deleteDashboardConfig`

Requires platform configuration write access. Deleting a missing key succeeds.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Configuration is absent. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

