# POST /admin/v1/databaseParameters

**Resource:** [databaseParameters](../resources/databaseParameters.md)
**Create database parameter**
**Operation ID:** `createDatabaseParameter`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [databaseParameterItem](../schemas/databaseParameterItem/databaseParameterItem.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | create database parameter successfully |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[databaseParameterItem](../schemas/databaseParameterItem/databaseParameterItem.md)

