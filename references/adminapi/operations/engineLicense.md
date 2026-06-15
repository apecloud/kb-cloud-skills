# GET /admin/v1/engineLicense

**Resource:** [engineLicense](../resources/engineLicense.md)
**Get engineLicense**
**Operation ID:** `engineLicense`

Get a engineLicense detail

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `licenseId` | query | string | Yes | license id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[engineLicense](../schemas/engineLicense/engineLicense.md)

