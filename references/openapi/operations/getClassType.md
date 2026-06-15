# GET /api/v1/classTypes/{id}

**Resource:** [classTypes](../resources/classTypes.md)
**Get a class type by ID**
**Operation ID:** `getClassType`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[classType](../schemas/classType/classType.md)

