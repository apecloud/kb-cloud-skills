# accountOption

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `maxSuperUserAccount` | integer (int32) | No | number of super user accounts cloud create.
If not set, use default value.
If set to 0, it means not allowed to create super user account.
 |
| `enabled` | boolean | Yes |  |
| `privileges` | string[] | No |  |
| `maxLen` | integer (int32) | No | max length of account name.
If not set, use default value.
 |
| `minLen` | integer (int32) | No | min length of account name.
If not set, use default value.
 |
| `accountNamePattern` | string | Yes |  |
| `create` | boolean | Yes |  |
| `resetPassword` | boolean | Yes |  |
| `delete` | boolean | Yes |  |
| `supportLock` | boolean | No | Whether the engine supports account lock and unlock actions. |
| `supportServiceAccount` | boolean | No | Whether the engine supports service account access-key management. |
| `protectedAccounts` | string[] | No | Account names that are protected from update, delete, lock, and unlock actions. |
| `displayRootAccount` | boolean | No |  |
| `resetRootPassword` | boolean | No |  |
| `supportMultipleComponent` | boolean | No |  |
| `excludeRootAccounts` | string[] | No |  |

