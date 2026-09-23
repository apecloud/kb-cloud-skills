# MilvusRoleCreateRequest

Milvus role create request.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | Milvus role name. |
| `grants` | MilvusRoleGrant[] | No | Native Milvus privilege grants owned by this role. |

