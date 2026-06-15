# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/export

**Resource:** [dms](../resources/dms.md)
**Data Export**
**Operation ID:** `DataExport`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `id` | path | string | Yes | id of the datasource |

## Request Body

**Content Types:** `application/json`

**Schema:** [DmsExportRequest](../schemas/Dms/DmsExportRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | data in format |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

