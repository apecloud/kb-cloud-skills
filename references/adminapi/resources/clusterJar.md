# clusterJar

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/jars/config` | Get external JAR capability and configuration | [View](../operations/getClusterJarConfig.md) |
| GET | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/jars` | List external JAR versions with metadata and per-instance synchronization state | [View](../operations/listClusterJars.md) |
| POST | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/jars` | Upload an immutable JAR version | [View](../operations/uploadClusterJar.md) |
| DELETE | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/jars/{jarId}` | Delete an unpublished JAR version | [View](../operations/deleteClusterJar.md) |
| GET | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/jars/{jarId}/download` | Download the original JAR | [View](../operations/downloadClusterJar.md) |
| POST | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/jars/{jarId}/distribute` | Publish a JAR with optimistic manifest version checking | [View](../operations/distributeClusterJar.md) |
| POST | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/jars/{jarId}/retry` | Retry synchronization of published JARs | [View](../operations/retryClusterJar.md) |
| POST | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/jars/{jarId}/archive` | Archive a JAR while retaining published files and startup synchronization | [View](../operations/archiveClusterJar.md) |
