# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/history

**Resource:** [dms](../resources/dms.md)
**list the query History**
**Operation ID:** `listQueryHistory`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `id` | path | string | Yes | id of the datasource |
| `limit` | query | integer (int64) | No | maximum history records to return, default and max 100 |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[DmsQueryHistoryList](../schemas/Dms/DmsQueryHistoryList.md)

