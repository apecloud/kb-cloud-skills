# GET /admin/v1/environments/{environmentName}/nodeGroups

**Resource:** [environment](../resources/environment.md)
**List environment node groups**
**Operation ID:** `listNodeGroups`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |
| `zones` | query | string[] | No | available zones for filtering node groups |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned when environment is created successfully. |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [nodeGroup](../schemas/nodeGroup/nodeGroup.md)

