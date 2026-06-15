# PATCH /admin/v1/organizations/{orgName}/clusters/{clusterName}/ipWhitelist/{ipWhitelistId}

**Resource:** [ipWhitelist](../resources/ipWhitelist.md)
**Update IP whitelist**
**Operation ID:** `updateIPWhitelist`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |
| `ipWhitelistId` | path | string | Yes | ID of the IP whitelist |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | Name of the whitelist |
| `description` | string | No | Description |
| `addresses` | string[] | Yes | Whitelist IP Addresses |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned when object is updated successfully. |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[ipWhitelist](../schemas/ipWhitelist/ipWhitelist.md)

