# sqlAuditParameterOption

Parameter configuration for querying and controlling (required when type is parameter). When type is parameter, both query and control (reconfigure) are inferred from this configuration.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `configSpec` | string | Yes | Configuration spec name |
| `configFileName` | string | Yes | Configuration file name |
| `key` | string | Yes | Parameter key to query |
| `enabledValues` | string[] | No | List of parameter values that indicate SQL audit is enabled (case-insensitive comparison) |
| `disabledValues` | string[] | No | List of parameter values that indicate SQL audit is disabled (case-insensitive comparison) |
| `processOrder` | boolean | No | If true, process parameter value from left to right, supporting subtraction (e.g., pgaudit.log with -read). Each part modifies the current state. Final state determines if audit is enabled. Default is false. |
| `allValue` | string | No | Special value that enables all classes when processOrder is true (e.g., "all" for pgaudit.log). If this value is encountered, it enables all audit classes. Optional, only used when processOrder is true. |

