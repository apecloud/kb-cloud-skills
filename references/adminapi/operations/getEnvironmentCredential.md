# GET /admin/v1/environments/{environmentName}/credentials/{credentialName}

**Resource:** [environment](../resources/environment.md)
**Get environment credential**
**Operation ID:** `getEnvironmentCredential`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |
| `credentialName` | path | string | Yes | name of the environment credential |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[environmentCredential](../schemas/environmentCredential/environmentCredential.md)

