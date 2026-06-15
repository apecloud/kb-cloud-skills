# POST /api/v1/organizations/{orgName}/replication/channel/objects

**Resource:** [dataReplication](../resources/dataReplication.md)
**query replication object**
**Operation ID:** `queryReplicationObject`

query replication object.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The Name of the organization |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [replicationObjectQuery](../schemas/replicationObjectQuery/replicationObjectQuery.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 501 | (reference) |

**Success Response Schema:**

[replicationObjectTree](../schemas/replicationObjectTree/replicationObjectTree.md)

