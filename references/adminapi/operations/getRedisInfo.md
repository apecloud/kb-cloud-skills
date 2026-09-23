# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/redis/info

**Resource:** [dms](../resources/dms.md)
**get Redis INFO output by section**
**Operation ID:** `getRedisInfo`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `id` | path | string | Yes |  |
| `database` | query | integer (int64) | No | Logical Redis database index. INFO is server-level; the parameter is accepted for API consistency. |
| `section` | query | string | No |  |
| `nodeId` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[RedisInfoResponse](../schemas/Redis/RedisInfoResponse.md)

