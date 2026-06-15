# database

Cluster Database APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/databases` | List cluster databases | [View](../operations/listDatabases.md) |
| POST | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/databases` | Create cluster database | [View](../operations/createDatabase.md) |
| GET | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/databases/{databaseName}` |  | [View](../operations/getDatabase.md) |
| DELETE | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/databases/{databaseName}` | Delete cluster database | [View](../operations/deleteDatabase.md) |
| PATCH | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/databases/{databaseName}` | update database config | [View](../operations/updateDatabaseConfig.md) |
