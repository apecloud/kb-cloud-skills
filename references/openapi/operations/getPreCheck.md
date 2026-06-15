# GET /api/v1/organizations/{orgName}/replication/channel/precheck/{preCheckID}

**Resource:** [dataReplication](../resources/dataReplication.md)
**get preCheck**
**Operation ID:** `getPreCheck`

get preCheck.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `preCheckID` | path | string | Yes | The ID of the preCheck task |
| `orgName` | path | string | Yes | The Name of the organization |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[preCheckTaskDetail](../schemas/preCheckTaskDetail/preCheckTaskDetail.md)

