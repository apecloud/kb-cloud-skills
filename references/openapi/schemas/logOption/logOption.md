# logOption

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `component` | string | Yes |  |
| `error` | boolean | Yes |  |
| `slow` | boolean | Yes |  |
| `slowTemplate` | boolean | No | Whether slow log template is supported. |
| `slowExplain` | boolean | No | Whether slow log SQL EXPLAIN is supported. |
| `audit` | boolean | Yes |  |
| `running` | boolean | Yes |  |
| `sqlAuditSwitch` | [sqlAuditSwitchOption](sqlAuditSwitchOption.md) | No |  |

