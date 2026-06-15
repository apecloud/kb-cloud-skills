# event

event is the information of operation event

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | ID of the event |
| `resourceId` | string | No | ID of the resource |
| `resourceType` | [eventResourceType](eventResourceType.md) | No |  |
| `resourceTypeDescription` | [localizedDescription](localizedDescription.md) | No |  |
| `resourceName` | string | No | Name of the resource |
| `operator` | string | No | operator of the event, if source is user, operator is user name; if source is system, operator is system name |
| `operatorId` | string | No | The user ID of the operator |
| `details` | string | No | Details will include the extra event info, such as update cluster which field, OpsRequest content etc |
| `hasTask` | boolean | No | hasTask is true if the event has a task |
| `result` | string | No | result of the operation event |
| `eventName` | string | No | Event name is OpsRequest name or cluster operation name |
| `displayName` | string | No | Display name is custom operation name |
| `orgName` | string | No | The org of the event |
| `resultStatus` | [eventResultStatus](eventResultStatus.md) | No |  |
| `source` | [eventSource](eventSource.md) | No |  |
| `end` | string (date-time) | No | event end time |
| `start` | string (date-time) | No | event start time |
| `createdAt` | string (date-time) | No | event created time |

