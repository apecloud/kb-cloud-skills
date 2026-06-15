# POST /admin/v1/environments

**Resource:** [environment](../resources/environment.md)
**Create environment**
**Operation ID:** `createEnvironment`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [environmentCreate](../schemas/environmentCreate/environmentCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned when environment is created successfully. |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[environment](../schemas/environment/environment.md)

