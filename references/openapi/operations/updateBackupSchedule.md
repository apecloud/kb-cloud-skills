# PATCH /api/v1/organizations/{orgName}/clusters/{clusterName}/backupSchedules/{scheduleName}

**Resource:** [backup](../resources/backup.md)
**Update backup schedule**
**Operation ID:** `updateBackupSchedule`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the org |
| `clusterName` | path | string | Yes | name of the cluster |
| `scheduleName` | path | string | Yes | name of the backup schedule |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [backupScheduleUpdate](../schemas/backupScheduleUpdate/backupScheduleUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[backupSchedule](../schemas/backupSchedule/backupSchedule.md)

