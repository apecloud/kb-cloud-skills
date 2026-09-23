# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/postgresql/sqlAnalysis/queries/{queryID}/explain

**Resource:** [diagnostics](../resources/diagnostics.md)
**Explain PostgreSQL SQL fingerprint**
**Operation ID:** `explainDiagnosticsPostgresqlSQLFingerprint`

Explicitly trigger a safe PostgreSQL EXPLAIN for one SQL fingerprint. The request does not accept raw SQL. DMS resolves the exact server-side parameterized SELECT statement identity independently of the ranking window, produces an estimated standard or generic plan without parameter sample values, rejects multiple statements, and never runs EXPLAIN ANALYZE or the original SQL. The plan uses current catalog statistics and the DMS connection context; it does not reconstruct the original role, search_path, session settings, parameter values, or historical actual plan.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |
| `queryID` | path | string | Yes | PostgreSQL pg_stat_statements queryid represented as a string. |
| `database` | query | string | Yes | Database name from the ranking row. The key is required to disambiguate the queryID. An unresolved empty name returns 422 no_explainable_sql_statement. |
| `user` | query | string | Yes | Database user from the ranking row. The key is required to disambiguate the queryID. An unresolved empty name returns 422 no_explainable_sql_statement. |
| `topLevel` | query | boolean | Yes | Top-level identity from the ranking row. Required to disambiguate the queryID on PostgreSQL versions that expose pg_stat_statements.toplevel. |
| `fingerprint` | query | string | No | Optional fingerprint consistency guard. Currently aligned with PostgreSQL pg_stat_statements queryid. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | Unprocessable Entity |
| 500 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

[postgresqlSQLFingerprintExplainResponse](../schemas/postgresqlSQLFingerprintExplainResponse/postgresqlSQLFingerprintExplainResponse.md)

