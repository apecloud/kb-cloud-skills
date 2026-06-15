# inspection

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/inspectionScripts` | list inspection scripts | [View](../operations/listInspectionScripts.md) |
| POST | `/admin/v1/inspectionScripts` | Create inspection script | [View](../operations/createInspectionScript.md) |
| DELETE | `/admin/v1/inspectionScripts/{scriptId}` | Delete inspection script | [View](../operations/deleteInspectionScript.md) |
| PATCH | `/admin/v1/inspectionScripts/{scriptId}` | Update inspection script | [View](../operations/updateInspectionScript.md) |
| GET | `/admin/v1/autoInspections` | list auto inspections | [View](../operations/listAutoInspections.md) |
| POST | `/admin/v1/autoInspections` | Create inspection cron job | [View](../operations/createAutoInspection.md) |
| GET | `/admin/v1/autoInspection` | get auto inspection | [View](../operations/getAutoInspection.md) |
| DELETE | `/admin/v1/autoInspections/{id}` | delete auto inspection | [View](../operations/deleteAutoInspection.md) |
| PATCH | `/admin/v1/autoInspections/{id}` | update auto inspection | [View](../operations/updateAutoInspection.md) |
| GET | `/admin/v1/organizations/{orgName}/inspectionTasksByOrg` | list inspection tasks by org | [View](../operations/listInspectionTasksByOrg.md) |
| POST | `/admin/v1/organizations/{orgName}/inspectionTasksByOrg` | create inspection task by org | [View](../operations/createInspectionTaskByOrg.md) |
| GET | `/admin/v1/organizations/{orgName}/inspectionTasksByOrg/{taskId}` | get inspection task by org | [View](../operations/getInspectionTaskByOrg.md) |
| GET | `/admin/v1/environments/{environmentName}/inspectionTasksByEnv` | list inspection tasks by env | [View](../operations/listInspectionTasksByEnv.md) |
| POST | `/admin/v1/environments/{environmentName}/inspectionTasksByEnv` | create inspection task by env | [View](../operations/createInspectionTaskByEnv.md) |
| GET | `/admin/v1/environments/{environmentName}/inspectionTasksByEnv/{taskId}` | get inspection task by env | [View](../operations/getInspectionTaskByEnv.md) |
| GET | `/admin/v1/inspectionTasks/aggregate` | get aggregate task result | [View](../operations/getAggregateTaskResult.md) |
