# GET /api/v1/inspectionScripts

**Resource:** [inspection](../resources/inspection.md)
**list inspection scripts**
**Operation ID:** `listInspectionScripts`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgNames` | query | string | No | name of the Org, multiple orgs separated by ',', if not provided, return all scripts |
| `engines` | query | string | No | query by, such as "node"/"mysql", multiple engines separated by ',' |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [inspectionScript](../schemas/inspectionScript/inspectionScript.md)

