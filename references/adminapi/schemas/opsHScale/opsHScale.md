# opsHScale

OpsHScale is the payload to horizontally scale a KubeBlocks cluster. It requires specifying either the number of replicas or the number of shards.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `component` | string | Yes | component type |
| `backupName` | string | No | name of the backup to restore from |
| `replicas` | integer | No | number of replicas |
| `onlineInstancesToOffline` | string[] | No | List of online instance names to be switched to offline during scaling in. |
| `OfflineInstancesToOnline` | string[] | No | List of offline instance names to be switched to online during scaling out. |
| `shards` | integer | No | number of shards, mutually exclusive with replicas. |
| `preConditionDeadlineSeconds` | integer | No | Specifies the maximum time in seconds that the OpsRequest will wait for its pre-conditions to be met before it aborts the operation |
| `force` | boolean | No | force the scaling operation without pre-check |
| `schedule` | [taskSchedule](taskSchedule.md) | No |  |

