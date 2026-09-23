# RedisAnalysisResponse

Instant Redis key analysis report sampled by bounded SCAN. This aligns with RedisInsight-style analysis dimensions but is not a persisted historical report.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `db` | integer (int64) | No |  |
| `filter` | [RedisAnalysisFilter](RedisAnalysisFilter.md) | No |  |
| `delimiter` | string | No | Actual delimiter used to aggregate top namespaces. |
| `progress` | [RedisAnalysisProgress](RedisAnalysisProgress.md) | No |  |
| `createdAt` | string (date-time) | No |  |
| `connectedClients` | integer (int64) | No | Connected client count from Redis INFO when available. |
| `totalKeys` | [RedisAnalysisTypedSummary](RedisAnalysisTypedSummary.md) | No |  |
| `totalMemory` | [RedisAnalysisTypedSummary](RedisAnalysisTypedSummary.md) | No |  |
| `topKeysNsp` | RedisAnalysisNamespaceSummary[] | No |  |
| `topMemoryNsp` | RedisAnalysisNamespaceSummary[] | No |  |
| `topKeysLength` | RedisAnalysisKey[] | No |  |
| `topKeysMemory` | RedisAnalysisKey[] | No |  |
| `expirationGroups` | RedisAnalysisExpirationGroup[] | No |  |
| `warnings` | string[] | No |  |
| `recommendations` | string[] | No |  |

