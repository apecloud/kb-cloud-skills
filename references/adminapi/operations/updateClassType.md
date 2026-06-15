# PATCH /admin/v1/classTypes/{id}

**Resource:** [classTypes](../resources/classTypes.md)
**Update a class type by ID**
**Operation ID:** `updateClassType`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/json`

**Schema:** [createClassType](../schemas/createClassType/createClassType.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[classType](../schemas/classType/classType.md)

