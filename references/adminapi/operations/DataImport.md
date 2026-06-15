# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/import

**Resource:** [dms](../resources/dms.md)
**Data Import**
**Operation ID:** `DataImport`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `id` | path | string | Yes | id of the datasource |

## Request Body

**Required:** Yes

**Content Types:** `application/json`, `multipart/form-data`

**Schema:** [DmsImportRequest](../schemas/Dms/DmsImportRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | create import task success, wait for task complete... |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

**Success Response Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `taskId` | string | No | the task id |

