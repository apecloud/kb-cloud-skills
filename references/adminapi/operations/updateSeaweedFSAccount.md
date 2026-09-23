# PATCH /admin/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}

**Resource:** [seaweedfs](../resources/seaweedfs.md)
**updateSeaweedFSAccount**
**Operation ID:** `updateSeaweedFSAccount`

Resets the secret for extra.accessKey. Account.name must match accountName. extra.accessKey is required. The returned password is disclosed only in this response.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the organization |
| `clusterName` | path | string | Yes | name of the cluster |
| `accountName` | path | string | Yes | name of the account |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [account](../schemas/account/account.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Selected credential updated |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

[account](../schemas/account/account.md)

