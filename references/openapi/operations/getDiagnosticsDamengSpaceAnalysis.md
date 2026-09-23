# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/dameng/spaceAnalysis

**Resource:** [diagnostics](../resources/diagnostics.md)
**Get Dameng space analysis**
**Operation ID:** `getDiagnosticsDamengSpaceAnalysis`

Get a read-only Dameng space snapshot including tablespace usage, schema sizes, top tables, and top indexes. Queries dba_free_space, dba_data_files, DBA_SEGMENTS, DBA_TABLES, DBA_INDEXES, and DBA_IND_COLUMNS.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |
| `tableLimit` | query | integer (int64) | No | Maximum number of top tables to return (0 or omitted = not collected) |
| `indexLimit` | query | integer (int64) | No | Maximum number of top indexes to return (0 or omitted = not collected) |
| `schema` | query | string | No | Filter tables and indexes by schema (owner). Omit or empty = all schemas. |
| `skipBasic` | query | boolean | No | Set to true to skip tablespace and schema queries, returning only tables and indexes. |

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

[damengSpaceAnalysis](../schemas/damengSpaceAnalysis/damengSpaceAnalysis.md)

