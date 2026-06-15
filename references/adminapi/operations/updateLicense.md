# POST /admin/v1/license

**Resource:** [license](../resources/license.md)
**Update license**
**Operation ID:** `updateLicense`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [licenseRequest](../schemas/licenseRequest/licenseRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[license](../schemas/license/license.md)

