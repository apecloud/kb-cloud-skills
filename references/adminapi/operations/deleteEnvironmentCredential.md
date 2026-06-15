# DELETE /admin/v1/environments/{environmentName}/credentials/{credentialName}

**Resource:** [environment](../resources/environment.md)
**Delete environment credential**
**Operation ID:** `deleteEnvironmentCredential`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |
| `credentialName` | path | string | Yes | name of the environment credential |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when environment credential is deleted successfully. |
| 403 | (reference) |
| 404 | (reference) |

