# POST /api/v1/ai/conversations

**Resource:** [AI](../resources/AI.md)
**Create a new conversation**
**Operation ID:** `newAIConversation`

Creates a new conversation.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [AIConversationRequest](../schemas/AIConversationRequest/AIConversationRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful operation |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[aiConversation](../schemas/aiConversation/aiConversation.md)

