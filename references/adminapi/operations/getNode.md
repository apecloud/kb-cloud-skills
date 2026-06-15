# GET /admin/v1/environments/{environmentName}/nodes/{nodeName}

**Resource:** [environment](../resources/environment.md)
**Get node info**
**Operation ID:** `getNode`

Get specified node info for environment

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |
| `nodeName` | path | string | Yes | name of the environment node |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Success |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[jsonBody](../schemas/jsonBody/jsonBody.md)

