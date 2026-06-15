# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/sqlAudit

**Resource:** [cluster](../resources/cluster.md)
**Get SQL audit log status**
**Operation ID:** `getSqlAudit`

Query the SQL audit log switch status for a cluster component

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |
| `component` | query | string | Yes | component type |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[sqlAuditStatus](../schemas/sqlAuditStatus/sqlAuditStatus.md)

