# POST /admin/v1/environments/{environmentName}/resourceStats/collect

**Resource:** [resourceStats](../resources/resourceStats.md)
**Collect resource statistics of environment**
**Operation ID:** `collectResourceStats`

Triggers an immediate collection of resource statistics for the specified environment.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | The name of the environment |

## Responses

| Status | Description |
|--------|-------------|
| 204 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

