# GET /admin/v1/data/damengdb/organizations/{orgName}/clusters/{clusterName}/tablespaces/{tablespaceName}

**Resource:** [dameng](../resources/dameng.md)
**Get Dameng tablespace info**
**Operation ID:** `getTablespace`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |
| `tablespaceName` | path | string | Yes | Tablespace name |

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

[DmTablespace](../schemas/Dm/DmTablespace.md)

