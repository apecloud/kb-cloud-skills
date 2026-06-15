# GET /admin/v1/data/damengdb/organizations/{orgName}/clusters/{clusterName}/tablespaces

**Resource:** [dameng](../resources/dameng.md)
**List damengdb tablespaces**
**Operation ID:** `listTablespaces`

List tablespaces for a Dameng cluster.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[DmTablespaceList](../schemas/Dm/DmTablespaceList.md)

