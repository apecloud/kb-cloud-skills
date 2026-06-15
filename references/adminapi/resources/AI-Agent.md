# AI Agent

Chat With AI Agent APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/organizations/{orgName}/ai-agent/status` | Get AI diagnosis agent status | [View](../operations/getAIAgentStatus.md) |
| GET | `/admin/v1/organizations/{orgName}/ai-agent/conversations` | List AI diagnosis conversations | [View](../operations/listAIAgentConversations.md) |
| POST | `/admin/v1/organizations/{orgName}/ai-agent/conversations` | Create an AI diagnosis conversation | [View](../operations/createAIAgentConversation.md) |
| GET | `/admin/v1/organizations/{orgName}/ai-agent/conversations/{conversationId}` | Get an AI diagnosis conversation | [View](../operations/getAIAgentConversation.md) |
| DELETE | `/admin/v1/organizations/{orgName}/ai-agent/conversations/{conversationId}` | Delete an AI diagnosis conversation | [View](../operations/deleteAIAgentConversation.md) |
| GET | `/admin/v1/organizations/{orgName}/ai-agent/conversations/{conversationId}/messages` | List AI diagnosis conversation messages | [View](../operations/listAIAgentMessages.md) |
| POST | `/admin/v1/organizations/{orgName}/ai-agent/conversations/{conversationId}/messages` | Send a user message and start or continue AI diagnosis | [View](../operations/sendAIAgentMessage.md) |
| GET | `/admin/v1/organizations/{orgName}/ai-agent/conversations/{conversationId}/turn-actions` | List stable AI diagnosis turn process actions | [View](../operations/listAIAgentTurnActions.md) |
| GET | `/admin/v1/organizations/{orgName}/ai-agent/conversations/{conversationId}/turn-actions/{actionId}` | Get one stable AI diagnosis turn process action | [View](../operations/getAIAgentTurnAction.md) |
| GET | `/admin/v1/organizations/{orgName}/ai-agent/conversations/{conversationId}/turn-actions/{actionId}/artifacts/{artifactId}/browse` | Browse a generated AI diagnosis report artifact | [View](../operations/browseAIAgentTurnActionArtifact.md) |
| GET | `/admin/v1/organizations/{orgName}/ai-agent/conversations/{conversationId}/turn-actions/{actionId}/artifacts/{artifactId}/download` | Download a generated AI diagnosis report artifact | [View](../operations/downloadAIAgentTurnActionArtifact.md) |
| GET | `/admin/v1/organizations/{orgName}/ai-agent/conversations/{conversationId}/events` | Subscribe to AI diagnosis conversation events | [View](../operations/subscribeAIAgentConversationEvents.md) |
| POST | `/admin/v1/organizations/{orgName}/ai-agent/conversations/{conversationId}/tool-confirmations/{confirmationId}/approve` | Approve one AI diagnosis tool confirmation | [View](../operations/approveAIAgentToolConfirmation.md) |
| POST | `/admin/v1/organizations/{orgName}/ai-agent/conversations/{conversationId}/tool-confirmations/{confirmationId}/reject` | Reject one AI diagnosis tool confirmation | [View](../operations/rejectAIAgentToolConfirmation.md) |
| POST | `/admin/v1/organizations/{orgName}/ai-agent/conversations/{conversationId}/stop` | Stop the current AI diagnosis turn | [View](../operations/stopAIAgentConversation.md) |
