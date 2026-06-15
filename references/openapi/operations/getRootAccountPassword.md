# GET /api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/root-password

**Resource:** [account](../resources/account.md)
**get root account password**
**Operation ID:** `getRootAccountPassword`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | name of the engine |
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |
| `accountName` | query | string | Yes | name of the account |
| `component` | query | string | No | name of the component |

## Responses

| Status | Description |
|--------|-------------|
| 200 | get root account password success |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

