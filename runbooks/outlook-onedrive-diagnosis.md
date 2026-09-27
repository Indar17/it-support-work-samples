# One-user Outlook and OneDrive diagnosis

**Status:** fictional work sample; fill this checklist only with authorized client information in their workspace.

## Scope before the session

- One named user and one device; record the Windows version and whether Outlook is classic, new or web.
- Ask what changed, the exact symptom and error, and whether other users are affected.
- Confirm the user controls the Microsoft account and can enter their own sign-in or MFA information.
- Ask about local PST files or unsynced folders before changing a profile or sync setting.
- Agree on a 30-minute diagnosis and what would require a new scope.

## Reversible checks

1. Check whether the mailbox and files are current in Outlook on the web and OneDrive on the web. This separates a local-client symptom from an account-wide problem.
2. Check network access, system clock, storage space and the app's actual signed-in account.
3. For Outlook, note the profile, cache range, connection status, add-ins and exact send/receive error. For OneDrive, inspect sync status, paused state, selected folders and conflict messages.
4. If a change is justified, explain what it affects, ensure local files are accounted for, and get the user's agreement before changing a profile or sync configuration.
5. Test the specific complaint again with the user. Record whether mail sends/receives and whether the affected file reaches the expected location.

## Handover fields

| Field | Record |
| --- | --- |
| Symptom and first observed time | To be filled during the client session |
| Checks and evidence | To be filled during the client session |
| Agreed actions | To be filled during the client session |
| Validation | To be filled with the user's test result |
| Remaining issue or escalation | To be filled if the issue is outside scope |

Never request a password, recovery code or MFA code. Do not delete a mailbox, PST, user profile or OneDrive folder as part of a short diagnosis.
