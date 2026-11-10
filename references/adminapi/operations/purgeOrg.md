# POST /admin/v1/organizations/{orgName}/purge

**Resource:** [organization](../resources/organization.md)
**Purge organization**
**Operation ID:** `purgeOrg`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [orgLifecycleRequest](../schemas/orgLifecycleRequest/orgLifecycleRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 202 | OK |
| 400 | (reference) |
| 403 | (reference) |
| 409 | (reference) |

