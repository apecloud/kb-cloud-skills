# GET /admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/computeGroups/{groupName}/accounts

**Resource:** [computeGroup](../resources/computeGroup.md)
**List compute group accounts**
**Operation ID:** `listComputeGroupAccounts`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | Supported engine name (doris or selectdb). |
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `groupName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[computeGroupAccountList](../schemas/computeGroupAccountList/computeGroupAccountList.md)

