# modeObjectStorageAdditionalHelmValuePath

The path in helm values that some object storage config will use. If empty, the values will not be set.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `bucket` | string | Yes | the bucket name for the object storage |
| `path` | string | No | root path where cluster stores data in the bucket. This field is not user-provided.
It is always set to cluster id. If not set, it means the engine does not support specify a path.
 |
| `usePathStyle` | string | No | whether the object storage is using path style or virtual host style.
If not set, it means the engine does not need this option.
 |
| `tlsEnabled` | string | No | whether the object storage endpoint uses TLS.
If not set, it means the engine does not need this option.
 |
| `tlsCACertSecret` | string | No | Secret name that stores the CA certificate for TLS object storage.
If not set, it means the engine does not need this option.
 |
| `tlsCACertSecretKey` | string | No | Secret key that stores the CA certificate for TLS object storage.
If not set, it means the engine does not need this option.
 |
| `region` | string | No | Region to use. If not set, it means the engine does not need this option.
 |

