# Security Policy

This document outlines important safety & security procedures you should take into account if finding security vulnerabilities on TaskBookly.

## Reporting a vulnerability

Reports may **NOT** be posted in public issues or discussions and instead should be reported in a [security advisory](https://github.com/CodeDevelops/TaskBookly-Community/security/advisories/new) in the **Security** tab.
This is because security vulnerabilities can cause serious damage and should only be reported privately to minimize spread & data mismanagement.

> [!CAUTION]
> The rule above is strictly enforced. Any issues or discussions opened describing or detailing security vulnerabilities will result in them being deleted and the author being banned from opening any more issues.

## What is considered a security vulnerability?

Below is a list of examples that are and are not considered security vulnerabilities.

### Symbols
⚠️ = Security Vulnerability (must be reported via a security advisory)<br>
🟢 = Not a vulnerability (should be reported in 'Issues' tab)

### Scenarios

| Scenario | 🔘 |
| --- | -------- |
| A user can successfully create an account with illegal characters that usually aren't allowed. | ⚠️ |
| A user found a loophole in server checks that allowed them to fetch private tasks from other users. | ⚠️ |
| A user can click on a submit button even though they haven't entered in any information. The server returns an error and doesn't fail internally. | 🟢 |

If you are not sure if you found a security vulnerability, please do not hesitate to open a security advisory and detail the issue there.

Keeping TaskBookly safe and secure is our top priority and is taken very seriously.
Thank you for helping us keep TaskBookly safe.