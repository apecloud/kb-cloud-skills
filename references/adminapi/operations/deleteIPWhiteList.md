# DELETE /admin/v1/organizations/{orgName}/clusters/{clusterName}/ipWhitelist/{ipWhitelistId}

**Resource:** [ipWhitelist](../resources/ipWhitelist.md)
**Delete IP whitelist**
**Operation ID:** `deleteIPWhiteList`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |
| `ipWhitelistId` | path | string | Yes | ID of the IP whitelist |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when object is deleted successfully. |
| 403 | (reference) |
| 404 | (reference) |

