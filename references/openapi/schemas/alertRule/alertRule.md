# alertRule

Alert rule information. Either provide 'expr' for custom expressions, or 'metric' for predefined metrics.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No |  |
| `summary` | string | No |  |
| `alertName` | string | Yes |  |
| `expr` | string | No | Expression. Required if metric is not provided. |
| `for` | string | Yes |  |
| `groupName` | string | Yes |  |
| `disabled` | boolean | No |  |
| `severity` | [alertSeverity](alertSeverity.md) | Yes |  |
| `createdAt` | string (date-time) | No |  |
| `updatedAt` | string (date-time) | No |  |
| `orgName` | string | No |  |

