# environmentModuleActionResult

Result of an environment module action. A successful dry run returns an empty object; an asynchronous action returns taskId; failed checks use the standard API error response.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `taskId` | string | No | ID of the submitted asynchronous module action task. It is absent for successful dry runs; failed checks return an API error. |

