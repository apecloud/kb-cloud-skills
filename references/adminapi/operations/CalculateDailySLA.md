# GET /admin/v1/sla/daily

**Resource:** [SLA](../resources/SLA.md)
**Calculate daily SLA for a environment or a cluster since a specific date**
**Operation ID:** `CalculateDailySLA`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | query | string[] | No | name of the environment |
| `startTime` | query | integer (int64) | Yes | SLA calculation start time Unix timestamp, unit is second. |
| `endTime` | query | integer (int64) | Yes | SLA calculation end time Unix timestamp, unit is second. |
| `clusterID` | query | string[] | No | id of the cluster |
| `engine` | query | string[] | No | database engine type |
| `orgName` | query | string[] | No | name of the organization |
| `timezoneOffset` | query | integer (int64) | No | timezone offset in seconds, e.g. offset of UTC+08:00 is +8 * 60 * 60, default is 0 |

## Responses

| Status | Description |
|--------|-------------|
| 200 | SLA calculated successfully |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[DailySLAList](../schemas/Daily/DailySLAList.md)

