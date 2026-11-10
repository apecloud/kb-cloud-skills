# aiAgentTurnActionList

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `items` | aiAgentTurnAction[] | Yes |  |
| `nextCursor` | string | No | Raw action cursor for the next page; independent of coalesced item IDs and timestamps. |
| `hasMore` | boolean | No | Whether more actions are available. Pages finish the last turn before coalescing, so item counts must not be used to detect the final page. |

