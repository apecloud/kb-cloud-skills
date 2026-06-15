# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/listObjectsForSelectiveBackup

**Resource:** [backup](../resources/backup.md)
**List objects tree for selective backup**
**Operation ID:** `listObjectsTreeForSelectiveBackup`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the org |
| `clusterName` | path | string | Yes | name of the cluster |
| `database` | query | string | No | database name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

