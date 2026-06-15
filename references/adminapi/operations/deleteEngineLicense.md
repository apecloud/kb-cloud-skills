# DELETE /admin/v1/engineLicense

**Resource:** [engineLicense](../resources/engineLicense.md)
**Delete engine license**
**Operation ID:** `deleteEngineLicense`

delete an engine license

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `licenseId` | query | string | Yes | license id |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when project is deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

