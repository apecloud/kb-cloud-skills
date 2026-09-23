# PUT /admin/v1/dashboardConfigs/{key}

**Resource:** [dashboardConfig](../resources/dashboardConfig.md)
**Create or replace dashboard configuration by key**
**Operation ID:** `putDashboardConfig`

Requires platform configuration write access. Atomic upsert with last-write-wins semantics. Request body is limited to 1 MiB.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dashboardConfigUpdate](../schemas/dashboardConfigUpdate/dashboardConfigUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Saved configuration. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[dashboardConfig](../schemas/dashboardConfig/dashboardConfig.md)

