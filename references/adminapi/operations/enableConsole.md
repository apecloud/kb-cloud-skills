# POST /admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/console

**Resource:** [dms](../resources/dms.md)
**enable console**
**Operation ID:** `enableConsole`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | name of the engine |
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |

## Request Body

**Content Types:** `application/json`

**Schema:** [DMSConsoleEnableOpt](../schemas/DMSConsoleEnableOpt/DMSConsoleEnableOpt.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | enable console successfully |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

