# GET /admin/v1/events

**Resource:** [event](../resources/event.md)
**List events**
**Operation ID:** `listEvents`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `status` | query | eventResultStatus | No | the status of the event |
| `customQuery` | query | string | No | Advanced query conditions, supporting all types of filterType. Such as "orgID:111 orgID:222 operatorID:333" |
| `pageNumber` | query | integer (int64) | No | the pageNumber of the query |
| `pageSize` | query | integer (int64) | No | the pageSize of the query |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful operation |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[eventList](../schemas/eventList/eventList.md)

