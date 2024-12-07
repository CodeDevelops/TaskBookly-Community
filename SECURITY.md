# Security Policy

This document outlines important safety & security procedures you should take into account if finding vulnerabilities on TaskBookly.

## Reporting a vulnerability

Reports may **NOT** be reported in Issues and should be reported via email to **report@taskbookly.com**.
This is because security vulnerabilities can cause serious issues and should only be reported privately to minimize spread & damage.

> [!CAUTION]
> The rule above is strictly inforced. Any issues opened detailing security vulnerabilities will result in them being deleted and the author being banned from opening any more issues.

## What is considered a security vulnerability?

Below is a list of examples that are and are not security vulnerabilities.

### Symbols
⚠️ = Security Vulnerability (must be reported via email)<br>
🟢 = Not a vulnerability (should be reported in 'Issues' tab)

### Scenerios

| Scenerio | 🔘 |
| --- | -------- |
| A user can successfully create an account with illegal characters that usually aren't allowed. | ⚠️ |
| A user found a loophole in server checks that allowed them to fetch private tasks from other users. | ⚠️ |
| A user can click on a submit button even though they haven't entered in any information. The server returns an error and doesn't fail internally. | 🟢 |
