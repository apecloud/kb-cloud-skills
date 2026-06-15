# GET /api/v1/autoInspections

**Resource:** [inspection](../resources/inspection.md)
**list auto inspections**
**Operation ID:** `listAutoInspections`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `resourceType` | query | autoInspectionResourceType | Yes | type of the auto inspection |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [autoInspection](../schemas/autoInspection/autoInspection.md)

