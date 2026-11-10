# PATCH /admin/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/groups/{groupName}/members

**Resource:** [dolphindb](../resources/dolphindb.md)
**DolphinDB ChangeGroupMembers**
**Operation ID:** `dolphinDBChangeGroupMembers`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `groupName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [DolphinDBMembershipChange](../schemas/Dolphin/DolphinDBMembershipChange.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Operation completed |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

