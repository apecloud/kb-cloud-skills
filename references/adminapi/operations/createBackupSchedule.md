# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/backupSchedules

**Resource:** [backup](../resources/backup.md)
**Create backup schedule**
**Operation ID:** `createBackupSchedule`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the org |
| `clusterName` | path | string | Yes | name of the cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [backupScheduleCreate](../schemas/backupScheduleCreate/backupScheduleCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[backupSchedule](../schemas/backupSchedule/backupSchedule.md)

