# POST /api/v1/environments/{environmentName}/organizations/{orgName}/engines/{engineName}/buildBackup

**Resource:** [backup](../resources/backup.md)
**build backup object with a existing backup directory**
**Operation ID:** `buildBackupObj`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `environmentName` | path | string | Yes | name of the environment |
| `engineName` | path | string | Yes | name of the engine |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `backupPath` | string | No | the backup directory path |
| `backupRepoName` | string | No | the backup repo name |
| `rootUserPassword` | string | No | the root user password of database |
| `clusterName` | string | No | the cluster name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[backup](../schemas/backup/backup.md)

