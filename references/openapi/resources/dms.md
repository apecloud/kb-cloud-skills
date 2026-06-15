# dms

Data Management System APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}` | get the datasource | [View](../operations/getDataSourceV2.md) |
| DELETE | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}` | delete the datasource | [View](../operations/deleteDataSourceV2.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource` | list the datasource of a cluster | [View](../operations/listDataSourceV2.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/testDS` | test the datasource | [View](../operations/testDataSourceV2.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/createDS` | create the datasource | [View](../operations/createDataSourceV2.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/updateDS` | update the datasource | [View](../operations/updateDataSourceV2.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/query` | create a SQL query | [View](../operations/query.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/export` | Data Export | [View](../operations/DataExport.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/import` | Data Import | [View](../operations/DataImport.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/task` | Get the task progress | [View](../operations/GetTaskProgress.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/tasks` | Get the task list | [View](../operations/GetTaskList.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/databases` | list all databases of the datasource | [View](../operations/listDmsDatabases.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/schemas` | list all databases or schema of the cluster | [View](../operations/getSchemaList.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/{schema}` | list the type and number of database objects in the specified database or schema | [View](../operations/ListObjectTypesInSchema.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/{schema}/{type}` | list the all name for the specified object type | [View](../operations/ListObjectNamesByType.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/{schema}/{type}/{objectName}` | get the detail object info | [View](../operations/GetObjectInfo.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/history` | list the query History | [View](../operations/listQueryHistory.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/sqlExplain` | explain a SQL | [View](../operations/sqlExplain.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/generateDDL` | support ddl and dml operations | [View](../operations/generateDDL.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/showData` | read data of table or view | [View](../operations/showData.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases` | list MongoDB databases | [View](../operations/listMongoDatabases.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/metadata` | list MongoDB database metadata | [View](../operations/listMongoDatabaseMetadata.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections` | list collections in a MongoDB database | [View](../operations/listMongoCollections.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections/{col}` | get MongoDB collection stats | [View](../operations/getMongoCollection.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections/{col}` | create MongoDB collection | [View](../operations/mongoCreateCollection.md) |
| DELETE | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections/{col}` | drop a MongoDB collection or view | [View](../operations/dropMongoCollection.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections/{col}/find` | find documents in a MongoDB collection | [View](../operations/mongoFind.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections/{col}/aggregate` | run MongoDB aggregation pipeline preview | [View](../operations/mongoAggregate.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections/{col}/insert` | insert MongoDB document(s) | [View](../operations/mongoInsert.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections/{col}/update` | update a single MongoDB document | [View](../operations/mongoUpdate.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections/{col}/delete` | delete a single MongoDB document | [View](../operations/mongoDelete.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections/{col}/replace` | replace a single MongoDB document | [View](../operations/mongoReplace.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections/{col}/indexes` | list MongoDB collection indexes | [View](../operations/mongoListIndexes.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections/{col}/indexes` | create MongoDB collection index | [View](../operations/mongoCreateIndex.md) |
| DELETE | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections/{col}/indexes/{indexName}` | drop MongoDB collection index | [View](../operations/mongoDropIndex.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections/{col}/schema` | analyze MongoDB collection schema from sample documents | [View](../operations/mongoAnalyzeSchema.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections/{col}/validation` | get MongoDB collection validation options | [View](../operations/mongoGetValidation.md) |
| PUT | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections/{col}/validation` | set MongoDB collection validation options | [View](../operations/mongoSetValidation.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/views` | create MongoDB view from a read-only aggregation pipeline | [View](../operations/mongoCreateView.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/explain` | explain a MongoDB query | [View](../operations/mongoExplain.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/shell/sessions` | create MongoDB mongosh runtime session | [View](../operations/mongoCreateShellSession.md) |
| DELETE | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/shell/sessions/{sessionID}` | close MongoDB mongosh runtime session | [View](../operations/mongoCloseShellSession.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/shell/sessions/{sessionID}/prompt` | get MongoDB mongosh session prompt | [View](../operations/mongoGetShellPrompt.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/shell/sessions/{sessionID}/evaluate` | evaluate input in a MongoDB mongosh session | [View](../operations/mongoEvaluateShell.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/shell/sessions/{sessionID}/completions` | get completions for a MongoDB mongosh session | [View](../operations/mongoCompleteShell.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/shell/sessions/{sessionID}/interrupt` | interrupt current MongoDB mongosh session operation | [View](../operations/mongoInterruptShell.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/sessions` | list all session for the cluster | [View](../operations/listSessionsOld.md) |
| DELETE | `/api/v1/organizations/{orgName}/clusters/{clusterName}/session/{session}` | close the session for the cluster | [View](../operations/closeSessions.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/tenant/{tenantId}/parameters` | list cluster parameters | [View](../operations/listParameters.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/tenant/{tenantId}/parameter` | alter cluster parameter | [View](../operations/alterParameter.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/tenant/{tenantId}/parameterHistory` | List parameters history of the Oceanbase tenant | [View](../operations/tenantParameterHistory.md) |
| GET | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/console` | get engine available console | [View](../operations/getEngineAvailableConsole.md) |
| POST | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/console` | enable console | [View](../operations/enableConsole.md) |
| DELETE | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/console` | disable console | [View](../operations/disableConsole.md) |
