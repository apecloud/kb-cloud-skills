# PATCH /admin/v1/environments/{environmentName}/modules

**Resource:** [environment](../resources/environment.md)
**Update an environment module**
**Operation ID:** `updateEnvironmentModule`

Performs the requested module action. Supported quick install and upgrade actions use dryRun=true for synchronous checks without changes; dryRun=false or omitted repeats the checks and submits an asynchronous task only when all checks pass. Other module actions keep their original behavior.

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
| 200 | The module action succeeded. A successful dry run returns an empty object; an asynchronous action returns taskId. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[environmentModuleActionResult](../schemas/environmentModuleActionResult/environmentModuleActionResult.md)

