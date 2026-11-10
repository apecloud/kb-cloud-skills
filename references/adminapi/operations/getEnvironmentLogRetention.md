# GET /admin/v1/environments/{environmentName}/logs/retention

**Resource:** [environment](../resources/environment.md)
**Get environment log retention**
**Operation ID:** `getEnvironmentLogRetention`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Log retention settings |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[logRetention](../schemas/logRetention/logRetention.md)

