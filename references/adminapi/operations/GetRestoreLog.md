# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/restore/{restoreId}/logs

**Resource:** [restore](../resources/restore.md)
**get restore workload logs of the cluster**
**Operation ID:** `GetRestoreLog`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |
| `restoreId` | path | string | Yes | id of the restore |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[restoreLog](../schemas/restoreLog/restoreLog.md)

