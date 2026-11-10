# GET /api/v1/data/oracle/organizations/{orgName}/clusters/{clusterName}/tablespaces/{tablespaceName}

**Resource:** [oracle](../resources/oracle.md)
**Get Oracle tablespace info**
**Operation ID:** `getOracleTablespace`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |
| `tablespaceName` | path | string | Yes | Tablespace name |

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

