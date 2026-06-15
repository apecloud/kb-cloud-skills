# GET /api/v1/organizations/{orgName}/events/{eventID}

**Resource:** [event](../resources/event.md)
**Query event detail by Event ID**
**Operation ID:** `getOrgEvent`

Retrieves detailed information about an event based on the provided Event ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization Name |
| `eventID` | path | string | Yes | Unique identifier for the event. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful operation |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[event](../schemas/event/event.md)

