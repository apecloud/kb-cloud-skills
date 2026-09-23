# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/mariadb/spaceAnalysis

**Resource:** [diagnostics](../resources/diagnostics.md)
**Get MariaDB space analysis**
**Operation ID:** `getDiagnosticsMariaDBSpaceAnalysis`

Get a read-only MariaDB compatible space snapshot and fixed backend-owned storage metrics.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `databaseName` | query | string | No | Optional database name for table and index details. When omitted, the largest non-system database is selected. |

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

[mysqlSpaceAnalysis](../schemas/mysqlSpaceAnalysis/mysqlSpaceAnalysis.md)

