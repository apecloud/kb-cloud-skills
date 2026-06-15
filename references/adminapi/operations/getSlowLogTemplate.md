# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/logs/slow/templates/{templateId}

**Resource:** [clusterLog](../resources/clusterLog.md)
**Get cluster slow log template**
**Operation ID:** `getSlowLogTemplate`

Get a slow log template of a cluster (VictoriaLogs backend only)

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `templateId` | path | string | Yes |  |
| `startTime` | query | string | Yes | Start time in epoch nanoseconds. |
| `endTime` | query | string | Yes | End time in epoch nanoseconds. |
| `componentName` | query | string | No |  |
| `instanceName` | query | string | No |  |
| `query` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful operation |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[clusterSlowLogTemplate](../schemas/clusterSlowLogTemplate/clusterSlowLogTemplate.md)

