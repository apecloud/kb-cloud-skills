# POST /admin/v1/data/damengdb/organizations/{orgName}/clusters/{clusterName}/tablespaces

**Resource:** [dameng](../resources/dameng.md)
**Create damengdb tablespace**
**Operation ID:** `createTablespace`

Create tablespace for a Dameng cluster.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |

## Request Body

**Content Types:** `application/json`

**Schema:** [DmTablespace](../schemas/Dm/DmTablespace.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[DmTablespace](../schemas/Dm/DmTablespace.md)

