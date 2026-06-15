# POST /api/v1/data/redis/organizations/{orgName}/clusters/{clusterName}/accounts

**Resource:** [redis](../resources/redis.md)
**create redis account**
**Operation ID:** `createRedisAccount`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | the name of organization |
| `clusterName` | path | string | Yes | the name of cluster |
| `component` | query | string | No | the component type to create account |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ACLUser](../schemas/ACLUser/ACLUser.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | create redis account success |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[opsRequestName](../schemas/opsRequestName/opsRequestName.md)

