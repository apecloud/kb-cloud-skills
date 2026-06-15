# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/tls

**Resource:** [tls](../resources/tls.md)
**Get cluster TLS certificate**
**Operation ID:** `getTLSCertificate`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[tlsCertList](../schemas/tlsCertList/tlsCertList.md)

