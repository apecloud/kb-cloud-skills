# GET /admin/v1/sla/uncompliant

**Resource:** [SLA](../resources/SLA.md)
**List uncompliant clusters**
**Operation ID:** `ListUncompliantClusters`

List uncompliant clusters that sla lower than the threshold

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | query | string[] | No | name of the environment |
| `engine` | query | string[] | No | database engine type |
| `orgName` | query | string[] | No | name of the organization |
| `startTime` | query | integer (int64) | Yes | SLA calculation start time Unix timestamp, unit is second. |
| `endTime` | query | integer (int64) | Yes | SLA calculation end time Unix timestamp, unit is second. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Uncompliant clusters retrieved successfully |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

Array of [SLA](../schemas/SLA/SLA.md)

