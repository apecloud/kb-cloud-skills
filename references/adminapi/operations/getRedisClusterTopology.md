# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/redis/cluster/topology

**Resource:** [dms](../resources/dms.md)
**get Redis Cluster topology**
**Operation ID:** `getRedisClusterTopology`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `id` | path | string | Yes |  |
| `database` | query | integer (int64) | No | Logical Redis database index. Redis Cluster topology only supports database 0. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[RedisClusterTopology](../schemas/Redis/RedisClusterTopology.md)

