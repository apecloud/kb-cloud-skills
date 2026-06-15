# GET /api/v1/organizations/{orgName}/checks/{checkID}

**Resource:** [dataReplication](../resources/dataReplication.md)
**Get Data Check**
**Operation ID:** `getDataCheck`

Retrieve a standalone data check detail.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The Name of the organization |
| `checkID` | path | string | Yes | The ID of the check |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A check detail. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[dataCheckItem](../schemas/dataCheckItem/dataCheckItem.md)

