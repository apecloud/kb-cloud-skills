# GET /admin/v1/autoInspection

**Resource:** [inspection](../resources/inspection.md)
**get auto inspection**
**Operation ID:** `getAutoInspection`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | query | string | No | id of the auto inspection |
| `orgName` | query | string | No | name of the Org |
| `envName` | query | string | No | name of the environment |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[autoInspection](../schemas/autoInspection/autoInspection.md)

