# GET /admin/v1/eventfilter/{filterType}

**Resource:** [event](../resources/event.md)
**Query available filters for event listing**
**Operation ID:** `getEventFilter`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `filterType` | path | eventFilterType | Yes | The event filter field you want to obtain. |
| `source` | query | string | Yes | The event filter you want to query from a certain source. |
| `resourceType` | query | string | No | The resource type you want to obtain. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful operation |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[eventFilterOptionList](../schemas/eventFilterOptionList/eventFilterOptionList.md)

