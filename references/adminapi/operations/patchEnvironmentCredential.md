# PATCH /admin/v1/environments/{environmentName}/credentials/{credentialName}

**Resource:** [environment](../resources/environment.md)
**Update environment credential**
**Operation ID:** `patchEnvironmentCredential`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |
| `credentialName` | path | string | Yes | name of the environment credential |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [environmentCredentialUpdate](../schemas/environmentCredentialUpdate/environmentCredentialUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[environmentCredential](../schemas/environmentCredential/environmentCredential.md)

