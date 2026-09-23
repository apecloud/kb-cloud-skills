# POST /api/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/access-keys

**Resource:** [seaweedfs](../resources/seaweedfs.md)
**createSeaweedFSAccessKey**
**Operation ID:** `createSeaweedFSAccessKey`

Creates a credential on the identity. Account.name must match accountName, role must be BASICUSER. Optional extra.accessKey and password select the access key and secret key; omitted or empty values are generated. The returned password is disclosed only in this response.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `accountName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [account](../schemas/account/account.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successful response |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

[account](../schemas/account/account.md)

