# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/redis/workbench/execute

**Resource:** [dms](../resources/dms.md)
**execute a Redis Workbench command**
**Operation ID:** `executeRedisWorkbenchCommand`

Executes a Redis command for the current datasource context. Follow-up implementation should record command history in datasource query_history with engine=redis; no Redis-specific history API is introduced by this contract.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `id` | path | string | Yes |  |
| `database` | query | integer (int64) | No | Logical Redis database index for this command. Redis Cluster only supports 0. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [RedisWorkbenchExecuteRequest](../schemas/Redis/RedisWorkbenchExecuteRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[RedisWorkbenchExecuteResponse](../schemas/Redis/RedisWorkbenchExecuteResponse.md)

