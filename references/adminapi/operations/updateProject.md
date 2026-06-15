# PATCH /admin/v1/environments/{environmentName}/projects/{projectName}

**Resource:** [project](../resources/project.md)
**Update a project in an environment**
**Operation ID:** `updateProject`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | environment name |
| `projectName` | path | string | Yes | project name |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [projectUpdate](../schemas/projectUpdate/projectUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[project](../schemas/project/project.md)

