# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/logs/slow/templates/{templateId}/explain

**Resource:** [clusterLog](../resources/clusterLog.md)
**Explain cluster slow log template**
**Operation ID:** `explainSlowLogTemplate`

Explain a slow log template sample using DMS. The SQL is selected by templateId and time range; request body does not accept raw SQL. Only MySQL-compatible and PostgreSQL SELECT samples are supported.

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

[clusterSlowLogExplainResponse](../schemas/clusterSlowLogExplainResponse/clusterSlowLogExplainResponse.md)

