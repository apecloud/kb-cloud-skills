# MongoAggregateRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `pipeline` | object[] | No | aggregation pipeline; write stages such as $out/$merge are rejected by DMS in S1 |
| `maxTimeMS` | integer (int64) | No | maximum aggregation execution time in milliseconds |
| `limit` | integer (int64) | No | optional preview result limit appended when pipeline has no terminal $limit |

