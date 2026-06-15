# GET /api/v1/organizations/{orgName}/checks/{checkID}/details

**Resource:** [dataReplication](../resources/dataReplication.md)
**Get Data Check Difference Details**
**Operation ID:** `getDataCheckDetails`

Read typed check miss or diff details from the latest parsed check result.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The Name of the organization |
| `checkID` | path | string | Yes | The ID of the check |
| `type` | query | dataCheckDetailType | Yes | The detail type |
| `schema` | query | string | No | Source schema or database. Required for snapshot checks. |
| `table` | query | string | No | Source table. Required for snapshot checks. |
| `key` | query | string | No | Struct object key. Optional for struct checks; omitted to page all struct details. |
| `page` | query | integer | No | Page number for pagination. |
| `pageSize` | query | integer | No | Number of items per page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[dataCheckDetails](../schemas/dataCheckDetails/dataCheckDetails.md)

