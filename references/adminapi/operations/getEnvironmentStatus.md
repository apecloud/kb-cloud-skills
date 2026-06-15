# GET /admin/v1/environments/{environmentName}/status

**Resource:** [environment](../resources/environment.md)
**Get environment status**
**Operation ID:** `getEnvironmentStatus`

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

[environmentStatus](../schemas/environmentStatus/environmentStatus.md)

