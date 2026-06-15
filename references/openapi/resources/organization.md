# organization

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v1/organizations` | List organizations of current user | [View](../operations/listOrg.md) |
| POST | `/api/v1/organizations` | Create organization | [View](../operations/createOrg.md) |
| GET | `/api/v1/organizations/{orgName}` | Get organization | [View](../operations/readOrg.md) |
| DELETE | `/api/v1/organizations/{orgName}` | Delete organization | [View](../operations/deleteOrg.md) |
| PATCH | `/api/v1/organizations/{orgName}` | Update organization | [View](../operations/patchOrg.md) |
| POST | `/api/v1/organizations/{orgName}/members/{memberId}/freeze` | freeze the member in org | [View](../operations/freezeMember.md) |
| POST | `/api/v1/organizations/{orgName}/members/{memberId}/unfreeze` | unfreeze the member in org | [View](../operations/unfreezeMember.md) |
