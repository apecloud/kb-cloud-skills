# PATCH /api/v1/autoInspections/{id}

**Resource:** [inspection](../resources/inspection.md)
**update auto inspection**
**Operation ID:** `updateAutoInspection`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | id of the auto inspection |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [autoInspection](../schemas/autoInspection/autoInspection.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[autoInspection](../schemas/autoInspection/autoInspection.md)

