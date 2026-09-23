# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/dameng/sessions/{sessionId}/lockAnalysis

**Resource:** [diagnostics](../resources/diagnostics.md)
**Get Dameng session lock analysis**
**Operation ID:** `getDiagnosticsDamengSessionLockAnalysis`

Get lock and blocking analysis for a Dameng session. Queries V$LOCK and V$SESSIONS to identify blocking/blocked relationships and lock details.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |
| `sessionId` | path | integer (int64) | Yes | Dameng session ID (SESS_ID) |

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

[damengLockAnalysis](../schemas/damengLockAnalysis/damengLockAnalysis.md)

