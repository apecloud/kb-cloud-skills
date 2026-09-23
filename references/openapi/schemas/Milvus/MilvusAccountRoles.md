# MilvusAccountRoles

Milvus account role update request.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `role` | string | No | Generic account role. SUPERUSER maps to the Milvus admin role. |
| `roles` | string[] | No | Milvus role names to assign to the user. Existing roles are replaced. |

