# GET /admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/dboptions

**Resource:** [rdbms](../resources/rdbms.md)
**get database options**
**Operation ID:** `getDatabaseOptions`

get available options for creating database

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | name of the engine |
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |
| `type` | query | string | Yes | option type |
| `charset` | query | string | No | specified charset |
| `filter` | query | string | No | filter keyword |

## Responses

| Status | Description |
|--------|-------------|
| 200 | get database options success |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema** (inline):

Array

