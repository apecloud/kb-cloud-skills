# POST /api/v1/ai/chatbi/v2

**Resource:** [AI](../resources/AI.md)
**SSE endpoint for Chat BI V2**
**Operation ID:** `chatBIV2SSE`

Establishes an SSE connection for AI BI conversation.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [chatRequest](../schemas/chatRequest/chatRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful operation, returns an event stream. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

