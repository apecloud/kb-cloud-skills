# DELETE /api/v1/data/postgresql/organizations/{orgName}/clusters/{clusterName}/extensions/{extensionName}

**Resource:** [postgresql](../resources/postgresql.md)
**drop PostgreSQL extension**
**Operation ID:** `dropPGExtension`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | name of the cluster |
| `extensionName` | path | string | Yes | The name of the PostgreSQL extension to uninstall. |
| `database` | query | string | Yes | The database where the extension is installed. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

