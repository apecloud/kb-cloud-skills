# POST /api/v1/data/postgresql/organizations/{orgName}/clusters/{clusterName}/extensions

**Resource:** [postgresql](../resources/postgresql.md)
**Enable PostgreSQL extensions in selected databases**
**Operation ID:** `createPGExtension`

Enable one or more PostgreSQL extensions across selected databases, returning a result for each database-extension pair.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | name of the cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [PgCreateExtensionOpt](../schemas/Pg/PgCreateExtensionOpt.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[createPgExtensionResp](../schemas/createPgExtensionResp/createPgExtensionResp.md)

