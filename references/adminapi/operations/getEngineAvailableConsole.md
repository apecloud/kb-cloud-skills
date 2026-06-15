# GET /admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/console

**Resource:** [dms](../resources/dms.md)
**get engine available console**
**Operation ID:** `getEngineAvailableConsole`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | name of the engine |
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[console](../schemas/console/console.md)

