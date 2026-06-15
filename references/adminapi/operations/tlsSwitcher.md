# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/tls

**Resource:** [tls](../resources/tls.md)
**Enable or disable cluster TLS**
**Operation ID:** `tlsSwitcher`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |

## Request Body

Enable TLS or not

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [tlsRequest](../schemas/tlsRequest/tlsRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |

