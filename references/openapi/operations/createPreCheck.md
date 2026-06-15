# POST /api/v1/organizations/{orgName}/replication/channel/precheck

**Resource:** [dataReplication](../resources/dataReplication.md)
**create pre check**
**Operation ID:** `createPreCheck`

create pre check.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The Name of the organization |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [preCheckCreate](../schemas/preCheckCreate/preCheckCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[preCheckTaskResponse](../schemas/preCheckTaskResponse/preCheckTaskResponse.md)

