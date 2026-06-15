# POST /admin/v1/autoInspections

**Resource:** [inspection](../resources/inspection.md)
**Create inspection cron job**
**Operation ID:** `createAutoInspection`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [autoInspection](../schemas/autoInspection/autoInspection.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[autoInspection](../schemas/autoInspection/autoInspection.md)

