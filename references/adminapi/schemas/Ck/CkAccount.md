# CkAccount

A ClickHouse account.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | The account (user) name. |
| `hostIp` | string[] | No | Host IPs the account is allowed to log in from. |
| `hostNames` | string[] | No | Host names the account is allowed to log in from. |
| `roles` | string | No | Roles granted to the account, separated by commas. |
| `type` | [CkAccountType](CkAccountType.md) | No |  |

