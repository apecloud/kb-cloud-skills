# inspection

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v1/inspectionScripts` | list inspection scripts | [View](../operations/listInspectionScripts.md) |
| POST | `/api/v1/inspectionScripts` | Create inspection script | [View](../operations/createInspectionScript.md) |
| DELETE | `/api/v1/inspectionScripts/{scriptId}` | Delete inspection script | [View](../operations/deleteInspectionScript.md) |
| PATCH | `/api/v1/inspectionScripts/{scriptId}` | Update inspection script | [View](../operations/updateInspectionScript.md) |
| POST | `/api/v1/autoInspections` | Create inspection cron job | [View](../operations/createAutoInspection.md) |
| GET | `/api/v1/autoInspection` | get auto inspection | [View](../operations/getAutoInspection.md) |
| DELETE | `/api/v1/autoInspections/{id}` | delete auto inspection | [View](../operations/deleteAutoInspection.md) |
| PATCH | `/api/v1/autoInspections/{id}` | update auto inspection | [View](../operations/updateAutoInspection.md) |
| GET | `/api/v1/organizations/{orgName}/inspectionTasksByOrg` | list inspection tasks by org | [View](../operations/listInspectionTasksByOrg.md) |
| POST | `/api/v1/organizations/{orgName}/inspectionTasksByOrg` | Trigger inspection for selected clusters in an organization | [View](../operations/createInspectionTaskByOrg.md) |
| GET | `/api/v1/organizations/{orgName}/inspectionTasksByOrg/{taskId}` | get inspection task by org | [View](../operations/getInspectionTaskByOrg.md) |
| GET | `/api/v1/inspectionTasks/aggregate` | get aggregate task result | [View](../operations/getAggregateTaskResult.md) |
