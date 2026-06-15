# PATCH /admin/v1/engines/resourceConstraints/{id}

**Resource:** [engine](../resources/engine.md)
**Update engine resource constraint**
**Operation ID:** `updateEngineResourceConstraint`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | id of the engine resource constraint |

## Request Body

Request body for engine resource constraint update

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [resourceConstraintUpdate](../schemas/resourceConstraintUpdate/resourceConstraintUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Operation completed successfully |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[resourceConstraint](../schemas/resourceConstraint/resourceConstraint.md)

