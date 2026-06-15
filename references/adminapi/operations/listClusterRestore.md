# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/restore

**Resource:** [restore](../resources/restore.md)
**List restore tasks**
**Operation ID:** `listClusterRestore`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[restoreList](../schemas/restoreList/restoreList.md)

