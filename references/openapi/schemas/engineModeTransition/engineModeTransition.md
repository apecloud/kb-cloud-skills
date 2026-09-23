# engineModeTransition

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `envRerender` | [envRerender](envRerender.md) | No |  |
| `mode` | string | Yes | Target mode name. |
| `waitComponentsRunningAfterModeChange` | string[] | No | Components that must be running once the mode change is done, in addition to the ones the
transition creates. Declare a component here when the transition re-renders it instead of
creating it, so it must settle before the transition is considered finished.
 |

