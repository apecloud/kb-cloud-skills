# DELETE /api/v1/ai/conversations/{conversationId}

**Resource:** [AI](../resources/AI.md)
**Delete a conversation**
**Operation ID:** `deleteConversation`

Deletes a specific conversation and all its associated messages.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `conversationId` | path | string (uuid) | Yes | ID of the conversation to delete |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Conversation deleted successfully |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

