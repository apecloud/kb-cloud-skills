# GET /api/v1/organizations/{orgName}/eventfilter/{filterType}

**Resource:** [event](../resources/event.md)
**Query available filters for event listing**
**Operation ID:** `getEventFilter`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The orgName |
| `filterType` | path | eventFilterType | Yes | The event filter field you want to obtain. OpenAPI do not support orgName. |
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

