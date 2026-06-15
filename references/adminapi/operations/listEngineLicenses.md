# GET /admin/v1/engineLicenses

**Resource:** [engineLicense](../resources/engineLicense.md)
**List all engineLicenses**
**Operation ID:** `listEngineLicenses`

list all engineLicenses

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | query | string | No | engine name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[engineLicenseList](../schemas/engineLicenseList/engineLicenseList.md)

