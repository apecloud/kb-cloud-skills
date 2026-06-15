# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/ipWhitelist

**Resource:** [ipWhitelist](../resources/ipWhitelist.md)
**List IP whitelists**
**Operation ID:** `listIPWhitelist`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[ipWhitelistList](../schemas/ipWhitelistList/ipWhitelistList.md)

