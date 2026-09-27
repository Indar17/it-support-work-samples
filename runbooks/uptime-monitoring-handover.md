# Small uptime-monitoring handover

**Status:** fictional template based on a small Uptime Kuma style setup. No production service or test result is claimed here.

## Agreed scope

- Server or VM owner, access method, host OS, maintenance window and backup/snapshot status.
- Up to two client-approved HTTP or host targets, expected check interval and an approved alert channel.
- One alert test and a short handover. This does not include 24/7 response or incident handling.

## Setup and check

1. Record where the monitoring service runs and who owns its updates, backups and credentials.
2. Configure each monitor with a meaningful name, target, method and expected response; avoid exposing secrets in monitor URLs.
3. Configure the agreed notification using a client-owned destination. Send a test notification and confirm the named recipient received it.
4. Trigger a controlled failure or use a safe test target, then observe the monitor's state and notification. Restore the test target and verify recovery. Agree on the test in advance.
5. Record the configuration and any gaps in a handover the client can maintain.

| Handover field | Record after a real setup |
| --- | --- |
| Host and owner | Pending |
| Targets and check intervals | Pending |
| Alert channel and recipient | Pending |
| Test time and observed result | Pending |
| Backup/restore path | Pending |
| Follow-up owner | Pending |

An alert is useful only when it reaches someone who can act. Keep monitoring credentials and notification tokens in the client's secret store, never in this repository.
