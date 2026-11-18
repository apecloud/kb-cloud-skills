# staticServiceClusterEngine

Optional engine filter for retained service clusters. Omitted or empty returns all supported MinIO, VictoriaMetrics, and VictoriaLogs candidates discovered from the kubeconfig and existing cluster records. The caller must explicitly select a cluster to reuse.

**Type:** enum

## Values

- ``
- `minio`
- `victoria-metrics`
- `victoria-logs`
