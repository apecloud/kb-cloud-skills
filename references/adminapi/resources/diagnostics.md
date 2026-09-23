# diagnostics

Diagnostics APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/mariadb/spaceAnalysis` | Get MariaDB space analysis | [View](../operations/getDiagnosticsMariaDBSpaceAnalysis.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/mariadb/sqlAnalysis` | Get MariaDB SQL analysis | [View](../operations/getDiagnosticsMariaDBSQLAnalysis.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/mariadb/performanceTrends` | Get MariaDB performance trends | [View](../operations/getDiagnosticsMariaDBPerformanceTrends.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/mysql/spaceAnalysis` | Get MySQL space analysis | [View](../operations/getDiagnosticsMysqlSpaceAnalysis.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/mssql/sessions` | List SQL Server sessions | [View](../operations/listDiagnosticsMssqlSessions.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/mssql/sessions/{sessionId}` | Get a SQL Server session | [View](../operations/getDiagnosticsMssqlSession.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/mssql/sessions/{sessionId}/lockAnalysis` | Get SQL Server blocking and locks | [View](../operations/getDiagnosticsMssqlSessionLockAnalysis.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/mssql/sessions/{sessionId}/requests/{requestId}/cachedPlan` | Read the cached compiled plan of a live SQL Server request | [View](../operations/getDiagnosticsMssqlSessionCachedPlan.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/postgresql/sessions` | List PostgreSQL session basic diagnostics | [View](../operations/listDiagnosticsPostgresqlSessions.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/postgresql/spaceAnalysis` | Get PostgreSQL space analysis | [View](../operations/getDiagnosticsPostgresqlSpaceAnalysis.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/postgresql/sqlAnalysis` | Get PostgreSQL SQL analysis | [View](../operations/getDiagnosticsPostgresqlSQLAnalysis.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/postgresql/sqlAnalysis/queries/{queryID}/explain` | Explain PostgreSQL SQL fingerprint | [View](../operations/explainDiagnosticsPostgresqlSQLFingerprint.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/mysql/sqlAnalysis` | Get MySQL SQL analysis | [View](../operations/getDiagnosticsMysqlSQLAnalysis.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/postgresql/performanceTrends` | Get PostgreSQL performance trends | [View](../operations/getDiagnosticsPostgresqlPerformanceTrends.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/mysql/performanceTrends` | Get MySQL performance trends | [View](../operations/getDiagnosticsMysqlPerformanceTrends.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/elasticsearch/taskAnalysis` | Get Elasticsearch task and hot-thread analysis | [View](../operations/getDiagnosticsElasticsearchTaskAnalysis.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/elasticsearch/storageAnalysis` | Get Elasticsearch storage and index analysis | [View](../operations/getDiagnosticsElasticsearchStorageAnalysis.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/elasticsearch/shards` | List Elasticsearch shards | [View](../operations/listDiagnosticsElasticsearchShards.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/elasticsearch/recoveries` | List active Elasticsearch shard recoveries | [View](../operations/listDiagnosticsElasticsearchRecoveries.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/elasticsearch/allocationExplain` | Explain Elasticsearch shard allocation | [View](../operations/explainDiagnosticsElasticsearchAllocation.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/postgresql/sessions/{pid}/lockAnalysis` | Get PostgreSQL session lock analysis | [View](../operations/getDiagnosticsPostgresqlSessionLockAnalysis.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/postgresql/sessions/{pid}` | Get PostgreSQL session basic diagnostics | [View](../operations/getDiagnosticsPostgresqlSession.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/dameng/spaceAnalysis` | Get Dameng space analysis | [View](../operations/getDiagnosticsDamengSpaceAnalysis.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/dameng/sqlAnalysis` | Get Dameng SQL analysis | [View](../operations/getDiagnosticsDamengSQLAnalysis.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/dameng/sessions/{sessionId}/lockAnalysis` | Get Dameng session lock analysis | [View](../operations/getDiagnosticsDamengSessionLockAnalysis.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/dameng/sessions/{sessionId}` | Get Dameng session detail | [View](../operations/getDiagnosticsDamengSession.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/dameng/sessions` | List Dameng sessions | [View](../operations/listDiagnosticsDamengSessions.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/kingbase/sessions` | List Kingbase session diagnostics | [View](../operations/listDiagnosticsKingbaseSessions.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/kingbase/sessions/{pid}/lockAnalysis` | Get Kingbase session lock analysis | [View](../operations/getDiagnosticsKingbaseSessionLockAnalysis.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/kingbase/sessions/{pid}` | Get Kingbase session diagnostics | [View](../operations/getDiagnosticsKingbaseSession.md) |
