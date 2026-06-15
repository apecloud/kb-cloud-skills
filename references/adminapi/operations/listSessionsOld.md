# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/sessions

**Resource:** [dms](../resources/dms.md)
**list all session for the cluster**
**Operation ID:** `listSessionsOld`
⚠️ **Deprecated**

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `all` | query | string | No | whether list all session includes sleep |

## Responses

| Status | Description |
|--------|-------------|
| 200 | list all session success |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[DmsSessionList](../schemas/Dms/DmsSessionList.md)

