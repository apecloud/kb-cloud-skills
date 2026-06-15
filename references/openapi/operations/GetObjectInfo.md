# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/{schema}/{type}/{objectName}

**Resource:** [dms](../resources/dms.md)
**get the detail object info**
**Operation ID:** `GetObjectInfo`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `id` | path | string | Yes | id of the datasource |
| `schema` | path | string | Yes | schema or database name |
| `type` | path | string | Yes | object type |
| `objectName` | path | string | Yes | object name |
| `database` | query | string | No | database name, used by engines such as MSSQL when reading object metadata inside a schema |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[DmsObjectResponse](../schemas/Dms/DmsObjectResponse.md)

