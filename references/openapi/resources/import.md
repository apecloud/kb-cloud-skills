# import

Data Import APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/import/preflight` | Data source preflight check | [View](../operations/importPreflight.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/import/preflight/{taskId}` | Get preflight task details | [View](../operations/getImportPreflightTask.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/import/objects` | Query replication objects for import | [View](../operations/queryImportObjects.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/import` | Query import task list | [View](../operations/listImportTask.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/import` | Create import task | [View](../operations/createImportTask.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/import/{id}` | Get import task details | [View](../operations/getImportTask.md) |
| DELETE | `/api/v1/organizations/{orgName}/clusters/{clusterName}/import/{id}` | Delete import task | [View](../operations/deleteImportTask.md) |
| PATCH | `/api/v1/organizations/{orgName}/clusters/{clusterName}/import/{id}/ops/{opsType}` | Create a import task operation | [View](../operations/updateImportTaskOps.md) |
