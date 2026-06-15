# organization

Organization APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/organizations` | Get organization list | [View](../operations/listOrganizations.md) |
| POST | `/admin/v1/organizations` | Create organization | [View](../operations/createOrg.md) |
| GET | `/admin/v1/organizations/{orgName}` | Get organization | [View](../operations/readOrg.md) |
| DELETE | `/admin/v1/organizations/{orgName}` | Delete organization | [View](../operations/deleteOrg.md) |
| PATCH | `/admin/v1/organizations/{orgName}` | Update organization | [View](../operations/patchOrg.md) |
| POST | `/admin/v1/organizations/{orgName}/enable` | enable the organization | [View](../operations/enableOrg.md) |
| POST | `/admin/v1/organizations/{orgName}/disable` | disable the organization | [View](../operations/disableOrg.md) |
| POST | `/admin/v1/organizations/{orgName}/members/{memberId}/freeze` | freeze the member in org | [View](../operations/freezeMember.md) |
| POST | `/admin/v1/organizations/{orgName}/members/{memberId}/unfreeze` | unfreeze the member in org | [View](../operations/unfreezeMember.md) |
