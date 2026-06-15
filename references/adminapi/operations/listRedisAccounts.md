# GET /admin/v1/data/redis/organizations/{orgName}/clusters/{clusterName}/accounts

**Resource:** [redis](../resources/redis.md)
**list redis accounts**
**Operation ID:** `listRedisAccounts`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | the name of organization |
| `clusterName` | path | string | Yes | the name of cluster |
| `component` | query | string | No | the component type to list accounts |

## Responses

| Status | Description |
|--------|-------------|
| 200 | list redis users success |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[ACLUserResponse](../schemas/ACLUserResponse/ACLUserResponse.md)

