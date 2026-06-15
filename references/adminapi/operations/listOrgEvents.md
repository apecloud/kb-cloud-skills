# GET /admin/v1/organizations/{orgName}/events

**Resource:** [event](../resources/event.md)
**List events**
**Operation ID:** `listOrgEvents`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization Name |
| `customQuery` | query | string | No | Advanced query conditions, supporting all types of filterType. Such as "operatorID:333 operatorID:444" |
| `status` | query | eventResultStatus | No | the status of the event |
| `pageNumber` | query | integer | No | the pageNumber of the query |
| `pageSize` | query | integer | No | the pageSize of the query |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful operation |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[eventList](../schemas/eventList/eventList.md)

