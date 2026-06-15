# DELETE /admin/v1/organizations/{orgName}/clusters/{clusterName}/backupSchedules/{scheduleName}

**Resource:** [backup](../resources/backup.md)
**Delete backup schedule**
**Operation ID:** `deleteBackupSchedule`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the org |
| `clusterName` | path | string | Yes | name of the cluster |
| `scheduleName` | path | string | Yes | name of the backup schedule |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when backup schedule is deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

