# globalPricing

the global information of pricing

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No | Enable global pricing |
| `currencyUnit` | string | No | The currency uint for display in bill query |
| `billScheduleTime` | string | Yes | Scheduled production time for daily bills, the format is 'HH:mm:ss', such as '01:00:00' meas every day at 1:00 AM, use the configured timezone |
| `lastBillingTime` | string (date-time) | No | The last billing time in RFC3339 format (e.g., '2025-09-01T00:00:00Z' or '2025-09-01T00:00:00+08:00').
This timestamp represents when the end time of the latest bill.
 |
| `cpuPrice` | string | Yes | The price of CPU, the unit is 'Core' |
| `memoryPrice` | string | Yes | The price of Memory, the unit is 'GB' |
| `storagePrice` | string | Yes | The price of Storage, the unit is 'GB' |
| `backupPrice` | string | Yes | The price of Backup, the unit is 'GB' |
| `timezone` | string | No | The timezone used for billing calculations and time alignment, specified as an IANA timezone identifier.

This timezone determines:
- When daily billing periods start and end (aligned to midnight in this timezone)
- How input timestamps are converted and normalized for billing calculations
- The timezone context for scheduled billing operations

Examples of valid timezone values:
- "UTC" - Coordinated Universal Time
- "Asia/Shanghai" - China Standard Time (CST, UTC+8)
- "America/New_York" - Eastern Time (EST/EDT, UTC-5/-4)
- "Europe/London" - Greenwich Mean Time/British Summer Time (GMT/BST, UTC+0/+1)

**The system defaults to UTC and not support to change for now.**
 |

