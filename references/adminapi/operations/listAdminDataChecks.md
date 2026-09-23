# GET /admin/v1/checks

**Resource:** [dataReplication](../resources/dataReplication.md)
**List Data Checks**
**Operation ID:** `listAdminDataChecks`

Retrieve a list of standalone data checks.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | query | string | No | The Name of the organization |
| `name` | query | string | No | The name of the check |
| `status` | query | string[] | No | The status of the check |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A list of checks. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[dataCheckList](../schemas/dataCheckList/dataCheckList.md)

