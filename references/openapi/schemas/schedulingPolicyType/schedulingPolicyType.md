# schedulingPolicyType

* `HardAntiAffinity` - Strictly enforce pod anti-affinity across nodes. Pods will not be scheduled when the anti-affinity constraints cannot be satisfied.
* `SoftAntiAffinity` - Prefer to spread pods across nodes using anti-affinity, but allow scheduling on the same node when constraints cannot be fully satisfied.
* `Disabled` - Do not apply pod anti-affinity constraints on nodes.


**Type:** enum

## Values

- `HardAntiAffinity`
- `SoftAntiAffinity`
- `Disabled`
