# DELETE /admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/sessions/{session}

**Resource:** [session](../resources/session.md)
**Kill cluster session**
**Operation ID:** `killSession`

kill a session in cluster

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | name of the engine |
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |
| `session` | path | string | Yes | session id |
| `keep` | query | boolean | No | if keep is true, the session will not be killed but only closed |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when session is killed successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

