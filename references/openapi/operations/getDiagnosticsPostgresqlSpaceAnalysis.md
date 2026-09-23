# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/postgresql/spaceAnalysis

**Resource:** [diagnostics](../resources/diagnostics.md)
**Get PostgreSQL space analysis**
**Operation ID:** `getDiagnosticsPostgresqlSpaceAnalysis`

Get a read-only PostgreSQL space snapshot from DMS and fixed backend-owned storage metrics. The response does not expose SQL, PromQL, storage history, or remediation actions.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |
| `databaseName` | query | string | No | Optional database name for selected table, index, and TOAST details. When omitted, the backend selects the largest connectable non-template database. |

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

[postgresqlSpaceAnalysis](../schemas/postgresqlSpaceAnalysis/postgresqlSpaceAnalysis.md)

