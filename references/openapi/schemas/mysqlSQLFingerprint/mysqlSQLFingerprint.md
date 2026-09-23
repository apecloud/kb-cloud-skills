# mysqlSQLFingerprint

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `queryID` | string | Yes | MySQL Performance Schema DIGEST value. |
| `fingerprint` | string | Yes | Stable SQL fingerprint identifier. M1 uses DIGEST. |
| `querySummary` | string | Yes | Normalized DIGEST_TEXT. Raw SQL text is intentionally not returned. |
| `calls` | integer (int64) | Yes | Number of executions accumulated in the current digest row. |
| `totalTimeMs` | number (double) | Yes | Total statement wait time in milliseconds. |
| `meanTimeMs` | number (double) | Yes | Mean statement wait time in milliseconds. |
| `maxTimeMs` | number (double) | Yes | Maximum statement wait time in milliseconds. |
| `rows` | integer (int64) | Yes | Sum of rows sent and rows affected. |
| `rowsSent` | integer (int64) | Yes | Total rows sent to clients. |
| `rowsAffected` | integer (int64) | Yes | Total rows affected by statements. |
| `rowsExamined` | integer (int64) | Yes | Total rows examined by statements. |
| `lockTimeMs` | number (double) | Yes | Total statement lock time in milliseconds. |
| `errors` | integer (int64) | Yes | Total statement errors. |
| `warnings` | integer (int64) | Yes | Total statement warnings. |
| `tmpTables` | integer (int64) | Yes | Total internal temporary tables created. |
| `tmpDiskTables` | integer (int64) | Yes | Total internal on-disk temporary tables created. |
| `noIndexUsed` | integer (int64) | Yes | Executions that used no index. |
| `noGoodIndexUsed` | integer (int64) | Yes | Executions for which no good index was found. |
| `database` | string | Yes | Default schema name associated with the digest row. |
| `firstSeen` | string | No | UTC timestamp when the digest was first observed. |
| `lastSeen` | string | No | UTC timestamp when the digest was most recently observed. |

