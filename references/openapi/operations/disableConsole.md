# DELETE /api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/console

**Resource:** [dms](../resources/dms.md)
**disable console**
**Operation ID:** `disableConsole`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | name of the engine |
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |

## Responses

| Status | Description |
|--------|-------------|
| 204 | disable console successfully |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

