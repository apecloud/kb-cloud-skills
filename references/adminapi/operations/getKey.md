# GET /admin/v1/keys/{keyName}

**Resource:** [key](../resources/key.md)
**get an existing key**
**Operation ID:** `getKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `keyName` | path | string | Yes | the name of key |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully updated the key |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[key](../schemas/key/key.md)

