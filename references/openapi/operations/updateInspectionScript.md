# PATCH /api/v1/inspectionScripts/{scriptId}

**Resource:** [inspection](../resources/inspection.md)
**Update inspection script**
**Operation ID:** `updateInspectionScript`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `scriptId` | path | string | Yes | id of the inspection script |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [inspectionScript](../schemas/inspectionScript/inspectionScript.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[inspectionScript](../schemas/inspectionScript/inspectionScript.md)

