# GET /admin/v1/environments/{environmentName}/modules/{moduleName}/pods/{podName}/logs

**Resource:** [environment](../resources/environment.md)
**Get logs for an environment module pod. When no parameters other than containerName and search are provided, start streaming logs in real-time.**
**Operation ID:** `getEnvironmentModuleLogs`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | Environment Name |
| `moduleName` | path | string | Yes | Environment module name |
| `podName` | path | string | Yes | Pod name |
| `containerName` | query | string | No | Container name |
| `sinceSeconds` | query | integer | No | Get logs from the last n seconds |
| `sinceTime` | query | string (date-time) | No | Get logs since this time (RFC3339 format) |
| `tailLines` | query | integer | No | Number of lines to return from the end |
| `search` | query | string | No | Search keyword in logs |
| `previous` | query | boolean | No | Get previous terminated container logs |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Success |
| 400 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[environmentModuleLogs](../schemas/environmentModuleLogs/environmentModuleLogs.md)

