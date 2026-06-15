# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/{schema}/{type}

**Resource:** [dms](../resources/dms.md)
**list the all name for the specified object type**
**Operation ID:** `ListObjectNamesByType`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `id` | path | string | Yes | id of the datasource |
| `schema` | path | string | Yes | schema or database name |
| `type` | path | string | Yes | object type |
| `database` | query | string | No | database name, used by engines such as MSSQL when listing object names inside a schema |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[DmsObjectNameList](../schemas/Dms/DmsObjectNameList.md)

