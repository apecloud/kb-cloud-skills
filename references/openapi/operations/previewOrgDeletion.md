# GET /api/v1/organizations/{orgName}/deletionPreview

**Resource:** [organization](../resources/organization.md)
**Preview organization deletion or purge**
**Operation ID:** `previewOrgDeletion`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `orgID` | query | string | Yes |  |
| `action` | query | orgDeletionAction | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Read-only preview; actual mutations revalidate all conditions |
| 400 | (reference) |
| 403 | (reference) |
| 409 | (reference) |

**Success Response Schema:**

[orgDeletionPreview](../schemas/orgDeletionPreview/orgDeletionPreview.md)

