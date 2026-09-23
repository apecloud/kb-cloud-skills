# ipPool

Provider-neutral Pod IP pool summary.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No |  |
| `ipFamily` | [ipPoolIPFamily](ipPoolIPFamily.md) | No |  |
| `subnet` | string | No |  |
| `disabled` | boolean | No |  |
| `default` | boolean | No |  |
| `allocatedIPCount` | integer (int64) | No |  |
| `totalIPCount` | integer (int64) | No |  |
| `availableIPCount` | integer (int64) | No |  |
| `capacityReliable` | boolean | No |  |
| `affinitySummary` | string[] | No |  |

