# DELETE /admin/v1/environments/{environmentName}/nodes

**Resource:** [environment](../resources/environment.md)
**Delete nodes from environment**
**Operation ID:** `deleteNodes`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |

## Request Body

**Content Types:** `application/json`

**Schema** (inline):

Array

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when nodes are deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

