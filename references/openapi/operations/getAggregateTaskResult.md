# GET /api/v1/inspectionTasks/aggregate

**Resource:** [inspection](../resources/inspection.md)
**get aggregate task result**
**Operation ID:** `getAggregateTaskResult`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `aggregateType` | query | aggregateTaskType | Yes | the type of the aggregate task |
| `engine` | query | string | No | the engine of the task |
| `resourceName` | query | string | No | only show the result of the specific organization or environment |
| `resultType` | query | aggregateTaskResultType | No | result of the task |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[aggregateTaskResultList](../schemas/aggregateTaskResultList/aggregateTaskResultList.md)

