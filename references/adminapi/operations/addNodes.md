# POST /admin/v1/environments/{environmentName}/nodes

**Resource:** [environment](../resources/environment.md)
**Add nodes to environment**
**Operation ID:** `addNodes`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [nodePool](../schemas/nodePool/nodePool.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | environment nodepool |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[nodePool](../schemas/nodePool/nodePool.md)

