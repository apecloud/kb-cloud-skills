# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/schemas

**Resource:** [dms](../resources/dms.md)
**list all databases or schema of the cluster**
**Operation ID:** `getSchemaList`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `id` | path | string | Yes | id of the datasource |
| `database` | query | string | No | database name, used by engines such as MSSQL when listing schemas inside a database |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[DmsSchemaList](../schemas/Dms/DmsSchemaList.md)

