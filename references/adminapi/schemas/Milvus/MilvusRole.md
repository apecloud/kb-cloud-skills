# MilvusRole

Milvus role with native privilege grants.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | Milvus role name. |
| `grants` | MilvusRoleGrant[] | Yes | Native Milvus privilege grants owned by this role. |

