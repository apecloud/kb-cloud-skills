# GET /admin/v1/environments/{environmentName}/statusHistory

**Resource:** [environment](../resources/environment.md)
**Get environment status history**
**Operation ID:** `getEnvironmentStatusHistory`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |
| `startTime` | query | string (date-time) | Yes | start time of the query range (nano seconds) |
| `endTime` | query | string (date-time) | Yes | end time of the query range(nano seconds) |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful operation |

**Success Response Schema:**

[environmentStatusHistory](../schemas/environmentStatusHistory/environmentStatusHistory.md)

