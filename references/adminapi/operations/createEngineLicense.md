# POST /admin/v1/engineLicense

**Resource:** [engineLicense](../resources/engineLicense.md)
**Create engineLicense**
**Operation ID:** `createEngineLicense`

Create a new engineLicense

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

**Schema:** [engineLicenseCreate](../schemas/engineLicenseCreate/engineLicenseCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[engineLicense](../schemas/engineLicense/engineLicense.md)

