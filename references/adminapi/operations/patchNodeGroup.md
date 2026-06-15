# PATCH /admin/v1/environments/{environmentName}/nodeGroups/{nodeGroupName}

**Resource:** [environment](../resources/environment.md)
**Patch node group**
**Operation ID:** `patchNodeGroup`

partially update the specified NodeGroup

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the NodeGroup |
| `nodeGroupName` | path | string | Yes | name of the node group |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [nodeGroupUpdate](../schemas/nodeGroupUpdate/nodeGroupUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[nodeGroup](../schemas/nodeGroup/nodeGroup.md)

