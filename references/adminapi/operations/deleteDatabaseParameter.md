# DELETE /admin/v1/databaseParameters

**Resource:** [databaseParameters](../resources/databaseParameters.md)
**Delete database parameter**
**Operation ID:** `deleteDatabaseParameter`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [deleteDatabaseParameterItem](../schemas/deleteDatabaseParameterItem/deleteDatabaseParameterItem.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when database parameter is deleted successfully. |
| 403 | (reference) |
| 404 | (reference) |

