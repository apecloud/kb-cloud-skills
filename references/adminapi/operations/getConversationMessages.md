# GET /admin/v1/ai/conversations/{conversationId}/messages

**Resource:** [AI](../resources/AI.md)
**Get AI conversation messages**
**Operation ID:** `getConversationMessages`

Retrieves ai messages for a specific conversation. If pre is not provided, returns the last 10 turn messages. If pre is provided, returns 10 turn messages after the pre message.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `conversationId` | path | string (uuid) | Yes | ID of the conversation |
| `pre` | query | string | No | Previous message ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A list of messages for the conversation |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[aiMessageListResponse](../schemas/aiMessageListResponse/aiMessageListResponse.md)

