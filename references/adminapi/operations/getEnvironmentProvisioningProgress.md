# GET /admin/v1/environments/{environmentName}/progress

**Resource:** [environment](../resources/environment.md)
**Get environment provisioning progress**
**Operation ID:** `getEnvironmentProvisioningProgress`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[jsonBody](../schemas/jsonBody/jsonBody.md)

