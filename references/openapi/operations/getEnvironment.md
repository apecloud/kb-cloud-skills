# GET /api/v1/organizations/{orgName}/environments/{environmentName}

**Resource:** [environment](../resources/environment.md)
**Get environment**
**Operation ID:** `getEnvironment`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `environmentName` | path | string | Yes | name of the Environment |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[environment](../schemas/environment/environment.md)

