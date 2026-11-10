# clickhouseSource

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | Source expression, for example clusterAllReplicas('ck', system.processes). |
| `kind` | string | No | Logical source kind (system table or collection step). |
| `status` | string | No | Collection status (success, partial, failed). |
| `message` | string | No | Short human-readable status detail. |

