# SQL Injection

## Severity

High

## Description

The assessment included testing the application's SQL Injection lesson within OWASP WebGoat as part of the controlled lab exercise.

## Impact

Successful SQL injection can expose or modify backend data and bypass intended application logic.

## Evidence

See the `Screenshots/` and `Evidence/` directories.

## Remediation

- Use parameterized queries.
- Validate input.
- Apply least-privilege database permissions.

## References

- OWASP SQL Injection Prevention Cheat Sheet
