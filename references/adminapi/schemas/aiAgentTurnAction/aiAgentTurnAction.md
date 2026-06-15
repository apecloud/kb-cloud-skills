# aiAgentTurnAction

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `actionId` | string | Yes |  |
| `conversationId` | string | Yes |  |
| `turnId` | string | Yes |  |
| `messageId` | string | No |  |
| `type` | [aiAgentEventType](aiAgentEventType.md) | Yes |  |
| `status` | string | No |  |
| `title` | string | Yes |  |
| `summary` | string | No |  |
| `toolName` | string | No |  |
| `target` | string | No |  |
| `confirmationId` | string | No |  |
| `hasDetail` | boolean | Yes |  |
| `detail` | object | No | Sanitized action detail. Warning states are returned as `warning.value`
with stable values such as `output_truncated`, `final_analysis_missing`,
`no_tool_evidence`, `model_no_tool_call`, or `tooling_unavailable`.
`model_no_tool_call` and `tooling_unavailable` are turn-completed
warnings and are not emitted on tool/check detail cards.
The legacy `warningReason` string may be present for compatibility.
 |
| `createdAt` | string (date-time) | Yes |  |

