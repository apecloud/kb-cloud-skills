# chatResponse

Chat message response

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | any | Yes | Arbitrary event payload |
| `done` | boolean | Yes | Whether the SSE stream is complete |
| `type` | [chatResponseType](chatResponseType.md) | Yes |  |
| `messageID` | string | No | Message ID |
| `sessionId` | string | Yes | Session ID |

