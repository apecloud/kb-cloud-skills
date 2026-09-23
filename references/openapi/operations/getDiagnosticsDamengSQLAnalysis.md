# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/dameng/sqlAnalysis

**Resource:** [diagnostics](../resources/diagnostics.md)
**Get Dameng SQL analysis**
**Operation ID:** `getDiagnosticsDamengSQLAnalysis`

Get a read-only Dameng SQL analysis snapshot from V$SYSTEM_LONG_EXEC_SQLS (long-running SQL) and V$SYSTEM_LARGE_MEM_SQLS (high-memory SQL). The response does not expose execution plans or remediation actions.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |
| `limit` | query | integer (int64) | No | Maximum number of SQL entries per category. Defaults to 20. |

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

[damengSQLAnalysis](../schemas/damengSQLAnalysis/damengSQLAnalysis.md)

