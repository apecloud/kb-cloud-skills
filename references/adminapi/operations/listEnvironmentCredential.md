# GET /admin/v1/environments/{environmentName}/credentials

**Resource:** [environment](../resources/environment.md)
**List environment credentials**
**Operation ID:** `listEnvironmentCredential`

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

[environmentCredentialList](../schemas/environmentCredentialList/environmentCredentialList.md)

