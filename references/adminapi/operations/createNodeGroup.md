# POST /admin/v1/environments/{environmentName}/nodeGroups

**Resource:** [environment](../resources/environment.md)
**Create environment node group**
**Operation ID:** `createNodeGroup`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [nodeGroup](../schemas/nodeGroup/nodeGroup.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned when environment is created successfully. |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[nodeGroup](../schemas/nodeGroup/nodeGroup.md)

