# GET /admin/v1/environments/{environmentName}/projects

**Resource:** [project](../resources/project.md)
**List projects in an environment**
**Operation ID:** `listProjects`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | environment name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[projectList](../schemas/projectList/projectList.md)

