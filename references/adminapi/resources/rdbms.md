# rdbms

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/demo` | generate demo data | [View](../operations/generateDemoData.md) |
| GET | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/dboptions` | get database options | [View](../operations/getDatabaseOptions.md) |
| GET | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/databases` | List cluster databases | [View](../operations/listDatabases.md) |
| POST | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/databases` | Create cluster database | [View](../operations/createDatabase.md) |
| GET | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/databases/{databaseName}` |  | [View](../operations/getDatabase.md) |
| DELETE | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/databases/{databaseName}` | Delete cluster database | [View](../operations/deleteDatabase.md) |
| PATCH | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/databases/{databaseName}` | update database config | [View](../operations/updateDatabaseConfig.md) |
| GET | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts` | List cluster accounts | [View](../operations/listAccounts.md) |
| POST | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts` | Create cluster account | [View](../operations/createAccount.md) |
| DELETE | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | Delete cluster account | [View](../operations/deleteAccount.md) |
| PATCH | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | update cluster account | [View](../operations/updateAccount.md) |
| PATCH | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/privileges` | update account privileges | [View](../operations/updateAccountPrivileges.md) |
| PATCH | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/lock` | Lock cluster account | [View](../operations/lockAccount.md) |
| PATCH | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/unlock` | Unlock cluster account | [View](../operations/unlockAccount.md) |
| GET | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/sessions` | List cluster sessions | [View](../operations/listSessions.md) |
| DELETE | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/sessions/{session}` | Kill cluster session | [View](../operations/killSession.md) |
