# POST /admin/v1/environments/{environmentName}/projects

**Resource:** [project](../resources/project.md)
**Create a project in an environment**
**Operation ID:** `createProject`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | environment name |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [projectCreate](../schemas/projectCreate/projectCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | A successful response. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[project](../schemas/project/project.md)

