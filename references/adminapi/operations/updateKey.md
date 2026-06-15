# PATCH /admin/v1/keys/{keyName}

**Resource:** [key](../resources/key.md)
**Update an existing key**
**Operation ID:** `updateKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `keyName` | path | string | Yes | the name of key |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [key](../schemas/key/key.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully updated the key |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[key](../schemas/key/key.md)

