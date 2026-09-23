# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/dameng/sessions/{sessionId}

**Resource:** [diagnostics](../resources/diagnostics.md)
**Get Dameng session detail**
**Operation ID:** `getDiagnosticsDamengSession`

Get a single Dameng session detail by session ID from V$SESSIONS, including SQL text, transaction info, and client details.

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

[damengSessionDetail](../schemas/damengSessionDetail/damengSessionDetail.md)

