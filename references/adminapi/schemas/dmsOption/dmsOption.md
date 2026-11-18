# dmsOption

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | Yes |  |
| `protocol` | string | No |  |
| `feature` | object | No | Engine capabilities and audit policy. auditSensitiveColumns is an array of case-insensitive sensitive column names; auditHighRiskStatements is an array of engine-specific rules: SQL keyword prefixes, Redis command/subcommand prefixes (FLUSHALL, CONFIG SET), or MongoDB command names (dropDatabase, delete, dropIndexes, $out). MongoDB shell helpers map to native command names; dynamic scripts may remain unclassified. Built-in credential redaction always applies. |
| `defaultAccount` | string | No |  |

