# GET /admin/v1/engineLicenseEntities

**Resource:** [engine](../resources/engine.md)
**List all engine license entities by license ID**
**Operation ID:** `listEngineLicenseEntities`

list all engine license entities by license ID

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `licenseId` | query | string | Yes | license ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[engineLicenseEntityList](../schemas/engineLicenseEntityList/engineLicenseEntityList.md)

