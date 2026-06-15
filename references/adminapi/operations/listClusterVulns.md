# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/vulns

**Resource:** [vuln](../resources/vuln.md)
**List vulnerabilities which affected the cluster**
**Operation ID:** `listClusterVulns`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned when vulnerabilities which affected the cluster are listed successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[clusterVulns](../schemas/clusterVulns/clusterVulns.md)

