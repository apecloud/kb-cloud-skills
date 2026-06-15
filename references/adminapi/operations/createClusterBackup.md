# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/backups

**Resource:** [backup](../resources/backup.md)
**Create backup**
**Operation ID:** `createClusterBackup`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |
| `component` | query | string | No | name of the component |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [backupCreate](../schemas/backupCreate/backupCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[backup](../schemas/backup/backup.md)

