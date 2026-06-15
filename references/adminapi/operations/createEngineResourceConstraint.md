# POST /admin/v1/engines/resourceConstraints

**Resource:** [engine](../resources/engine.md)
**Create engine resource constraint**
**Operation ID:** `createEngineResourceConstraint`

## Request Body

Request body for engine resource constraint

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [resourceConstraintCreate](../schemas/resourceConstraintCreate/resourceConstraintCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[resourceConstraint](../schemas/resourceConstraint/resourceConstraint.md)

