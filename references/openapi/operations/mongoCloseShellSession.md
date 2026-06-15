# DELETE /api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/shell/sessions/{sessionID}

**Resource:** [dms](../resources/dms.md)
**close MongoDB mongosh runtime session**
**Operation ID:** `mongoCloseShellSession`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `id` | path | string | Yes |  |
| `sessionID` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | shell session closed |
| 404 | (reference) |
| 500 | (reference) |

