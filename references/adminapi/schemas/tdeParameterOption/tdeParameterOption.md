# tdeParameterOption

Parameter configuration for querying and controlling TDE.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `configSpec` | string | Yes | Configuration spec name |
| `configFileName` | string | Yes | Configuration file name |
| `key` | string | Yes | Primary parameter key used to query TDE status |
| `enabledValues` | string[] | No | List of parameter values that indicate TDE is enabled |
| `disabledValues` | string[] | No | List of parameter values that indicate TDE is disabled |

