# POST /admin/v1/data/oracle/organizations/{orgName}/clusters/{clusterName}/tablespaces

**Resource:** [oracle](../resources/oracle.md)
**Create Oracle tablespace**
**Operation ID:** `createOracleTablespace`

Create tablespace for a Oracle cluster.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [OracleTablespaceCreate](../schemas/Oracle/OracleTablespaceCreate.md)

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

[OracleTablespace](../schemas/Oracle/OracleTablespace.md)

