# GET /admin/v1/engineLicenseEntity

**Resource:** [engine](../resources/engine.md)
**Get an engine license entity by ID**
**Operation ID:** `getEngineLicenseEntity`

get an engine license entity by ID

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `entityId` | query | string | Yes | entity ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[engineLicenseEntity](../schemas/engineLicenseEntity/engineLicenseEntity.md)

