# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/dms/audits

**Resource:** [dms](../resources/dms.md)
**List independent DMS audit records**
**Operation ID:** `listDMSAudit`

Only organization administrators and authorized admin-portal users can read these records.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `offset` | query | integer | No |  |
| `limit` | query | integer | No |  |
| `userName` | query | string | No |  |
| `databaseUser` | query | string | No |  |
| `database` | query | string | No |  |
| `operation` | query | string | No |  |
| `statement` | query | string | No | Literal substring of recorded content. |
| `risk` | query | dmsAuditRisk | No |  |
| `status` | query | dmsAuditStatus | No |  |
| `from` | query | string (date-time) | No |  |
| `to` | query | string (date-time) | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Audit records, ordered by newest first. |
| 403 | (reference) |

**Success Response Schema:**

[dmsAuditList](../schemas/dmsAuditList/dmsAuditList.md)

