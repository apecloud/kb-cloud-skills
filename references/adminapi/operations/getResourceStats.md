# GET /admin/v1/environments/{environmentName}/resourceStats

**Resource:** [resourceStats](../resources/resourceStats.md)
**Get resource statistics of environment**
**Operation ID:** `getResourceStats`

Returns aggregated resource statistics for the specified environment within an organization.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | The name of the environment |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[environmentResourceStats](../schemas/environmentResourceStats/environmentResourceStats.md)

