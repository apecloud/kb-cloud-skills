# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/redis/keyAnalysis

**Resource:** [redisKeyAnalysis](../resources/redisKeyAnalysis.md)
**Create a Redis keys analysis task**
**Operation ID:** `adminCreateRedisKeyAnalysis`

Admin variant of createRedisKeyAnalysis.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |

## Request Body

**Content Types:** `application/json`

**Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `parameters` | object | No |  |

**`parameters` fields:**

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `topBigKey` | integer (int64) | No |  |
| `numOfElemMin` | integer (int64) | No |  |
| `bigKeySizeMin` | string | No |  |
| `topSlot` | integer (int64) | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Analysis task submitted. |
| 400 | (reference) |
| 404 | (reference) |

**Success Response Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `taskId` | string | Yes |  |
| `status` | string | No |  |

