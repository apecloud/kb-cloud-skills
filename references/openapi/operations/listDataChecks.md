# GET /api/v1/organizations/{orgName}/checks

**Resource:** [dataReplication](../resources/dataReplication.md)
**List Data Checks**
**Operation ID:** `listDataChecks`

Retrieve a list of standalone data checks.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The Name of the organization |
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

