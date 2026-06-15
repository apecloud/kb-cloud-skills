# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/backupSchedules

**Resource:** [backup](../resources/backup.md)
**List backup schedules**
**Operation ID:** `listBackupSchedules`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the org |
| `clusterName` | path | string | Yes | name of the cluster |
| `backupMethod` | query | string | No | filter by backup method |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[backupScheduleList](../schemas/backupScheduleList/backupScheduleList.md)

