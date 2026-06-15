# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/{schema}

**Resource:** [dms](../resources/dms.md)
**list the type and number of database objects in the specified database or schema**
**Operation ID:** `ListObjectTypesInSchema`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `id` | path | string | Yes | id of the datasource |
| `schema` | path | string | Yes | schema or database name |
| `database` | query | string | No | database name, used by engines such as MSSQL when listing objects inside a schema |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[DmsObjectList](../schemas/Dms/DmsObjectList.md)

