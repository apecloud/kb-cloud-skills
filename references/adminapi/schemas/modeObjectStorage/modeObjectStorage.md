# modeObjectStorage

object storage related configs


**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No | if object storage is enabled for this mode |
| `serviceRefs` | modeObjectStorageServiceRef[] | No | Object storage serviceRef configs supported by this mode. Use this when different object
storage engines may require different serviceRef or Helm value mappings. When it is set,
the cluster create request selects one item by objectStorageConfig.serviceRef.name.
 |

