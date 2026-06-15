# DELETE /admin/v1/keys/{keyName}

**Resource:** [key](../resources/key.md)
**Delete a specific key**
**Operation ID:** `deleteKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `keyName` | path | string | Yes | the name of key |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Successfully deleted the key |
| 401 | (reference) |
| 403 | (reference) |

