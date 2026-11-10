# PUT /admin/v1/environments/{environmentName}/logs/retention

**Resource:** [environment](../resources/environment.md)
**Set environment log retention**
**Operation ID:** `putEnvironmentLogRetention`

Replaces the current settings. Applies to the next cleanup.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [logRetention](../schemas/logRetention/logRetention.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Log retention settings |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[logRetention](../schemas/logRetention/logRetention.md)

