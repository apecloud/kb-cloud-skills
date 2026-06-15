# autoInspection

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `resourceType` | [autoInspectionResourceType](autoInspectionResourceType.md) | Yes |  |
| `resourceID` | string | No |  |
| `resourceName` | string | Yes |  |
| `creator` | string | Yes |  |
| `schedule` | string | No |  |
| `runEvery` | [autoInspectionRunUnit](autoInspectionRunUnit.md) | No |  |
| `daysOfWeek` | integer[] | No |  |
| `daysOfMonth` | integer[] | No |  |
| `hour` | integer | No |  |
| `minute` | integer | No |  |
| `savedDays` | integer | No |  |
| `nextRunTime` | string (date-time) | No |  |
| `enabled` | boolean | Yes |  |

