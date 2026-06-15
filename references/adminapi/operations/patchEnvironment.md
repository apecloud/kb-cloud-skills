# PATCH /admin/v1/environments/{environmentName}

**Resource:** [environment](../resources/environment.md)
**Update environment**
**Operation ID:** `patchEnvironment`

partially update the specified Environment

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [environmentUpdate](../schemas/environmentUpdate/environmentUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[environment](../schemas/environment/environment.md)

