# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/mysql/sqlAnalysis

**Resource:** [diagnostics](../resources/diagnostics.md)
**Get MySQL SQL analysis**
**Operation ID:** `getDiagnosticsMysqlSQLAnalysis`

Get a read-only MySQL SQL fingerprint ranking from Performance Schema statement digests. The response does not expose raw SQL text, time-window aggregation, execution plans, or remediation actions.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |
| `limit` | query | integer (int64) | No | Maximum number of SQL fingerprints to return. The backend applies its own upper bound. |
| `orderBy` | query | string | No | Sort key. Allowed values are totalTime, meanTime, maxTime, and calls. Defaults to totalTime. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[mysqlSQLAnalysis](../schemas/mysqlSQLAnalysis/mysqlSQLAnalysis.md)

