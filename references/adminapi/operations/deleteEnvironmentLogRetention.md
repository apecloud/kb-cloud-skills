# DELETE /admin/v1/environments/{environmentName}/logs/retention

**Resource:** [environment](../resources/environment.md)
**Reset environment log retention**
**Operation ID:** `deleteEnvironmentLogRetention`

Removes environment settings and returns the built-in defaults.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Default log retention settings |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[logRetention](../schemas/logRetention/logRetention.md)

