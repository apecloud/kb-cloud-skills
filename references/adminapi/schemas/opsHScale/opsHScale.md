# opsHScale

OpsHScale is the payload to horizontally scale a KubeBlocks cluster. Specify replicas or shards. Replica scaling requires explicit template targets when the current mode component declares instanceTemplate.ops hscale.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `component` | string | Yes | component type |
| `backupName` | string | No | name of the backup to restore from |
| `replicas` | integer | No | number of replicas |
| `instanceTemplates` | instanceTemplateReplicas[] | No | Explicit template replica targets, required when the current mode component instanceTemplate.ops includes hscale. Otherwise omit for component-level scaling. Requires top-level replicas and every name from instanceTemplate.names, without missing, extra, or duplicate names. Template replica counts must sum to the component target; equal distribution is not required by the API. Component and template changes are sent together in one OpsRequest using current Cluster replicas to calculate scaleIn/scaleOut deltas. Shard-count scaling cannot include this list. |
| `onlineInstancesToOffline` | string[] | No | List of online instance names to be switched to offline during scaling in. |
| `OfflineInstancesToOnline` | string[] | No | List of offline instance names to be switched to online during scaling out. |
| `shards` | integer | No | number of shards, mutually exclusive with replicas. |
| `preConditionDeadlineSeconds` | integer | No | Specifies the maximum time in seconds that the OpsRequest will wait for its pre-conditions to be met before it aborts the operation |
| `force` | boolean | No | force the scaling operation without pre-check |
| `schedule` | [taskSchedule](taskSchedule.md) | No |  |

