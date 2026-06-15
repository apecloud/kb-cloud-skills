# GET /admin/v1/sla/rank

**Resource:** [SLA](../resources/SLA.md)
**List SLA rank for a environment**
**Operation ID:** `ListSLARank`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | query | string[] | No | name of the environment |
| `engine` | query | string[] | No | database engine type |
| `orgName` | query | string[] | No | name of the organization |
| `startTime` | query | integer (int64) | Yes | SLA calculation start time Unix timestamp, unit is second. |
| `endTime` | query | integer (int64) | Yes | SLA calculation end time Unix timestamp, unit is second. |
| `limit` | query | integer (int32) | No | Number of items per page. |

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

[SLAList](../schemas/SLAList/SLAList.md)

