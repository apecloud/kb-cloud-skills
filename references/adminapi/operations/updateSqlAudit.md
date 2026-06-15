# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/sqlAudit

**Resource:** [cluster](../resources/cluster.md)
**Update SQL audit log status**
**Operation ID:** `updateSqlAudit`

Enable or disable SQL audit log for a cluster component

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [sqlAuditRequest](../schemas/sqlAuditRequest/sqlAuditRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[sqlAuditResponse](../schemas/sqlAuditResponse/sqlAuditResponse.md)

