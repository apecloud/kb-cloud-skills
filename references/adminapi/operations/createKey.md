# POST /admin/v1/keys

**Resource:** [key](../resources/key.md)
**Create a new key**
**Operation ID:** `createKey`

Store a new key in the system.

## Request Body

**Content Types:** `application/json`

**Schema:** [key](../schemas/key/key.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | key created successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[key](../schemas/key/key.md)

