# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/postgresql/performanceTrends

**Resource:** [diagnostics](../resources/diagnostics.md)
**Get PostgreSQL performance trends**
**Operation ID:** `getDiagnosticsPostgresqlPerformanceTrends`

Get read-only PostgreSQL performance trends from backend-owned Prometheus queries. The response does not expose SQL, PromQL, internal endpoints, or remediation actions.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |
| `range` | query | string | No | Controlled query range. Allowed values are 1h, 6h, 24h, and 7d. Defaults to 1h. |
| `step` | query | string | No | Controlled query granularity. Allowed values are 1m, 5m, 15m, and 1h. Defaults to 1m for 1h, 5m for 6h, 15m for 24h, and 1h for 7d. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[performanceTrends](../schemas/performanceTrends/performanceTrends.md)

