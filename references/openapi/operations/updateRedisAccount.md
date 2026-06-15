# PATCH /api/v1/data/redis/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}

**Resource:** [redis](../resources/redis.md)
**update redis account**
**Operation ID:** `updateRedisAccount`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | the name of organization |
| `clusterName` | path | string | Yes | the name of cluster |
| `accountName` | path | string | Yes | the name of account |
| `component` | query | string | No | in which component type to update account |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ACLUser](../schemas/ACLUser/ACLUser.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | update redis account success |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[opsRequestName](../schemas/opsRequestName/opsRequestName.md)

