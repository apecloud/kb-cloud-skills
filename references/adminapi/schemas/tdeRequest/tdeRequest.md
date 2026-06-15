# tdeRequest

Request to enable transparent data encryption. Disabling TDE is not supported.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `component` | string | Yes | Component type to update TDE for |
| `enable` | boolean | Yes | Whether to enable TDE. Must be true because disabling TDE is not supported. |

