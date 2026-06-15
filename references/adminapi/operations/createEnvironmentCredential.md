# POST /admin/v1/environments/{environmentName}/credentials

**Resource:** [environment](../resources/environment.md)
**Create environment credential**
**Operation ID:** `createEnvironmentCredential`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [environmentCredentialCreate](../schemas/environmentCredentialCreate/environmentCredentialCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned when environment credential is created successfully. |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[environmentCredential](../schemas/environmentCredential/environmentCredential.md)

