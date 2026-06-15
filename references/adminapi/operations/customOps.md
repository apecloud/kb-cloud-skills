# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/custom-ops

**Resource:** [opsrequest](../resources/opsrequest.md)
**Create custom OpsRequest**
**Operation ID:** `customOps`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [opsCustom](../schemas/opsCustom/opsCustom.md)

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

