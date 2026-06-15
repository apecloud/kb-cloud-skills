# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/databases

**Resource:** [dms](../resources/dms.md)
**list all databases of the datasource**
**Operation ID:** `listDmsDatabases`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `id` | path | string | Yes | id of the datasource |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[DmsSchemaList](../schemas/Dms/DmsSchemaList.md)

