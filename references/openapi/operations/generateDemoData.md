# POST /api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/demo

**Resource:** [rdbms](../resources/rdbms.md)
**generate demo data**
**Operation ID:** `generateDemoData`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | name of the engine |
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |
| `accountName` | query | string | Yes | acccount name which owns the database to generate demo data |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when demo data is generated successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

