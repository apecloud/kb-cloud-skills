# DELETE /admin/v1/environments/{environmentName}

**Resource:** [environment](../resources/environment.md)
**Delete environment**
**Operation ID:** `deleteEnvironment`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |

## Request Body

**Content Types:** `application/json`

**Schema:** [environmentDelete](../schemas/environmentDelete/environmentDelete.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when project is deleted successfully. |
| 403 | (reference) |
| 404 | (reference) |

