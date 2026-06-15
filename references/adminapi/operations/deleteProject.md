# DELETE /admin/v1/environments/{environmentName}/projects/{projectName}

**Resource:** [project](../resources/project.md)
**Delete a project in an environment**
**Operation ID:** `deleteProject`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | environment name |
| `projectName` | path | string | Yes | project name |

## Responses

| Status | Description |
|--------|-------------|
| 204 | A successful response. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

