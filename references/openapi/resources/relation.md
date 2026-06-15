# relation

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v1/organizations/{orgName}/cluster/{clusterName}/available-relations` | list the available clusters for the organization to create the a relation | [View](../operations/listAvailableClustersForRelation.md) |
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/relations` | list the clusters that have built a relation to the specified cluster | [View](../operations/listRelatedClusters.md) |
| POST | `/api/v1/organizations/{orgName}/clusters/{clusterName}/relations` | create a relation between the clusters in the organization | [View](../operations/createRelation.md) |
| DELETE | `/api/v1/organizations/{orgName}/clusters/{clusterName}/relation/{target}` | delete a existed relation between the clusters in the organization | [View](../operations/deleteRelation.md) |
