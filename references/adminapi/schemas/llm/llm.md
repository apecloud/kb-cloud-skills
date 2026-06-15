# llm

llm

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | ID of the llm |
| `name` | string | Yes | Name of the llm |
| `enabled` | boolean | Yes | Whether this LLM is enabled |
| `config` | object | Yes | Config.

For OpenAI-compatible providers, model entries under `available_models`
may include `max_tokens` as the maximum output token count and
`context_length` as the total context window. `context_window` is a
deprecated compatibility alias and should not be used by new clients.
 |
| `level` | [AccessLevel](AccessLevel.md) | No |  |
| `createdAt` | string (date-time) | No | CreatedAt is a timestamp representing the server time when this object was created. It is not guaranteed to be set in happens-before order across separate operations. Clients may not set this value. It is represented in RFC3339 form and is in UTC.

Populated by the system. Read-only. Null for lists |
| `updatedAt` | string (date-time) | No | UpdatedAt is a timestamp representing the server time when this object was created. It is not guaranteed to be set in happens-before order across separate operations. Clients may not set this value. It is represented in RFC3339 form and is in UTC.

Populated by the system. Read-only. Null for lists |

