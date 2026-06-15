# DELETE /api/v1/organizations/{orgName}/clusters/{clusterName}/session/{session}

**Resource:** [dms](../resources/dms.md)
**close the session for the cluster**
**Operation ID:** `closeSessions`
⚠️ **Deprecated**

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `session` | path | string | Yes | name of the storage volume |
| `keep` | query | string | No | whether only close the query and keep the session |

## Responses

| Status | Description |
|--------|-------------|
| 200 | close the session success |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

