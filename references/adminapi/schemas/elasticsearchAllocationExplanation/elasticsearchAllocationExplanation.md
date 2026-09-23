# elasticsearchAllocationExplanation

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `index` | string | No |  |
| `shard` | integer (int64) | No |  |
| `primary` | boolean | No |  |
| `currentState` | string | No |  |
| `currentNode` | [elasticsearchShardNode](elasticsearchShardNode.md) | No |  |
| `unassignedInfo` | [elasticsearchUnassignedInfo](elasticsearchUnassignedInfo.md) | No |  |
| `canAllocate` | string | No |  |
| `allocateExplanation` | string | No |  |
| `canRemainOnCurrentNode` | string | No |  |
| `canRemainDecisions` | elasticsearchAllocationDecider[] | No |  |
| `canRebalanceCluster` | string | No |  |
| `canRebalanceClusterDecisions` | elasticsearchAllocationDecider[] | No |  |
| `canRebalanceToOtherNode` | string | No |  |
| `rebalanceExplanation` | string | No |  |
| `nodeAllocationDecisions` | elasticsearchNodeAllocationDecision[] | No |  |

