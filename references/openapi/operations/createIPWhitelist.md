# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/ipWhitelist

**Resource:** [ipWhitelist](../resources/ipWhitelist.md)
**Create IP whitelist**
**Operation ID:** `createIPWhitelist`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |

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
| 201 | Returned when object is created successfully. |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[ipWhitelist](../schemas/ipWhitelist/ipWhitelist.md)

