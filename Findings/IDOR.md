# Insecure Direct Object Reference (IDOR)

## Severity

High

## Description

Authorization controls were reviewed to determine whether users could access resources belonging to other users by modifying object references.

The assessment focused on access control validation rather than authentication.

## Assessment Activities

- Resource authorization testing
- URL parameter review
- Identifier analysis

## Impact

Improper authorization may allow attackers to:

- Access sensitive information
- Modify another user's data
- Perform unauthorized actions

## Evidence

Supporting evidence is available within:

- Evidence/Burp/
- Screenshots/

## Recommendations

- Enforce server-side authorization checks.
- Avoid relying solely on user-supplied identifiers.
- Implement object-level access controls.

## References

- OWASP Broken Access Control
- CWE-639
