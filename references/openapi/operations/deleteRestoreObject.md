# DELETE /api/v1/organizations/{orgName}/clusters/{clusterName}/restore

**Resource:** [restore](../resources/restore.md)
**Delete restore task**
**Operation ID:** `deleteRestoreObject`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |
| `restoreName` | query | string | Yes | name of the restore |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

