# POST /admin/v1/engineLicenseEntity

**Resource:** [engine](../resources/engine.md)
**Create a new engine license entity**
**Operation ID:** `createEngineLicenseEntity`

create a new engine license entity

## Request Body

Engine license entity data

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [engineLicenseEntityCreate](../schemas/engineLicenseEntityCreate/engineLicenseEntityCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[engineLicenseEntity](../schemas/engineLicenseEntity/engineLicenseEntity.md)

