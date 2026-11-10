# apelocalCapacityObservation

A measurement over known nodes. Missing nodes are not treated as zero. Coverage counts nodes whose complete per-node inputs are known, not individual storage resources.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `value` | number (double) | No | Known-node sum in GiB or ratio in percent. Omitted when no inputs are known or a ratio denominator is zero. Ratios can exceed 100. Remaining quota is zero when there are selected nodes but none are ready. |
| `observedNodeCount` | integer | No | Number of nodes with all inputs for this measurement. |
| `expectedNodeCount` | integer | No | Number of selected nodes relevant to this measurement; only ready schedulable nodes for remaining quota. |
| `missingNodes` | string[] | No | Sorted names of relevant nodes with missing or inconsistent inputs for this measurement. |

