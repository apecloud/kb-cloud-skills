# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/dameng/sessions

**Resource:** [diagnostics](../resources/diagnostics.md)
**List Dameng sessions**
**Operation ID:** `listDiagnosticsDamengSessions`

List Dameng sessions from V$SESSIONS with lock status from V$LOCK. Returns session ID, user, state, client IP, transaction ID, lock status, SQL text, schema, duration, and more.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |
| `limit` | query | integer (int64) | No | Maximum number of sessions to return. Defaults to 200. |
| `state` | query | string | No | Filter sessions by state (e.g. ACTIVE, IDLE). Matches against V$SESSIONS.STATE. |

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

Array of [damengSessionListItem](../schemas/damengSessionListItem/damengSessionListItem.md)

