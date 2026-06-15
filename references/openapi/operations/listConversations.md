# GET /api/v1/ai/conversations

**Resource:** [AI](../resources/AI.md)
**List conversations by user**
**Operation ID:** `listConversations`

Retrieves a list of conversations filtered by user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Page number for pagination |
| `pageSize` | query | integer | No | Number of items per page |
| `type` | query | string | No | Type of conversations to filter, can be bi or analysis. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A list of conversations |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[aiConversationListResponse](../schemas/aiConversationListResponse/aiConversationListResponse.md)

