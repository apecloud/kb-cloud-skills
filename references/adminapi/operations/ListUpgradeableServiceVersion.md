# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/upgradeableServiceVersion

**Resource:** [engine](../resources/engine.md)
**list upgraded service version of the component**
**Operation ID:** `ListUpgradeableServiceVersion`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `clusterName` | path | string | Yes | Name of the cluster |
| `orgName` | path | string | Yes | organization name |
| `component` | query | string | Yes | component type |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[engineServiceVersions](../schemas/engineServiceVersions/engineServiceVersions.md)

