# PATCH /admin/v1/environments/{environmentName}/modules

**Resource:** [environment](../resources/environment.md)
**update environment module**
**Operation ID:** `updateEnvironmentModule`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | Environment Name |

## Request Body

**Content Types:** `application/json`

**Schema:** [environmentModuleUpdate](../schemas/environmentModuleUpdate/environmentModuleUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Success |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

**Success Response Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `taskId` | string | No | the task id |

