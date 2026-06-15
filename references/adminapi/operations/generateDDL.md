# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/generateDDL

**Resource:** [dms](../resources/dms.md)
**support ddl and dml operations**
**Operation ID:** `generateDDL`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `id` | path | string | Yes | id of the datasource |

## Request Body

**Content Types:** `application/json`

**Schema:** [DmsGenerateDDLRequest](../schemas/Dms/DmsGenerateDDLRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

