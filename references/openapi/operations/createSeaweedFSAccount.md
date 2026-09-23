# POST /api/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/accounts

**Resource:** [seaweedfs](../resources/seaweedfs.md)
**createSeaweedFSAccount**
**Operation ID:** `createSeaweedFSAccount`

Creates a BASICUSER identity with named policies from extra.policies. Optional extra.accessKey and password select the credential; empty values are generated. The password is disclosed only in this response.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the organization |
| `clusterName` | path | string | Yes | name of the cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [account](../schemas/account/account.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Identity and initial credential created |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

[account](../schemas/account/account.md)

