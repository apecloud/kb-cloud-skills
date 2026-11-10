# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/redis/keyAnalysis

**Resource:** [redisKeyAnalysis](../resources/redisKeyAnalysis.md)
**Create a Redis keys analysis task**
**Operation ID:** `createRedisKeyAnalysis`

Submits the redis-rdr-keys-analysis OpsDefinition. After the operation succeeds, the
platform reads /data/rdr-report.json from every primary pod and persists one
report row per shard. Poll the task and then call the report API with the returned taskId.


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

