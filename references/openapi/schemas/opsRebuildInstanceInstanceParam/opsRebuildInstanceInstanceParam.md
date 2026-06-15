# opsRebuildInstanceInstanceParam

instance params for RebuildInstance ops

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | Pod name of the instance |
| `targetNodeName` | string | No | The instance will rebuild on the specified node. If not set, it will rebuild on a random node. |

