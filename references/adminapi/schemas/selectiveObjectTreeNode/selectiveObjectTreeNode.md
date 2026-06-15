# selectiveObjectTreeNode

tree node for selective backup objects

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | string | Yes | the type of the node |
| `name` | string | Yes | the name of the node |
| `selectedAll` | boolean | No | whether all children nodes are selected |
| `children` | selectiveObjectTreeNode[] | No | children nodes |

