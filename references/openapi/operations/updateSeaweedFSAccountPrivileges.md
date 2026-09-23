# PATCH /api/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/privileges

**Resource:** [seaweedfs](../resources/seaweedfs.md)
**updateSeaweedFSAccountPrivileges**
**Operation ID:** `updateSeaweedFSAccountPrivileges`

Unsupported for SeaweedFS. Use the named policy binding API instead.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |
| `accountName` | path | string | Yes | name of the account |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [privilegeList](../schemas/privilegeList/privilegeList.md)

## Responses

| Status | Description |
|--------|-------------|
| 400 | (reference) |

