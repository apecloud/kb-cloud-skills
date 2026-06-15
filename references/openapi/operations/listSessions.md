# GET /api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/sessions

**Resource:** [session](../resources/session.md)
**List cluster sessions**
**Operation ID:** `listSessions`

list sessions in cluster

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | name of the engine |
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |
| `all` | query | boolean | No | whether list all session includes sleep |

## Responses

| Status | Description |
|--------|-------------|
| 200 | list all session success |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[DmsSessionList](../schemas/Dms/DmsSessionList.md)

