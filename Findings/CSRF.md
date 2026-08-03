# Cross-Site Request Forgery (CSRF)

## Severity

Medium

## Description

Cross-Site Request Forgery testing evaluated whether sensitive application actions were protected against unauthorized requests originating from external websites.

## Assessment Activities

- HTTP request analysis
- Token validation review
- Sensitive function assessment

## Impact

Without proper protections, attackers may perform unauthorized actions on behalf of authenticated users.

Potential impacts include:

- Account modification
- Password changes
- Unauthorized transactions

## Evidence

Relevant requests and responses are stored within:

- Evidence/Burp/
- Screenshots/

## Recommendations

- Implement anti-CSRF tokens.
- Use SameSite cookies.
- Validate request origin.
- Require re-authentication for sensitive operations.

## References

- OWASP CSRF Prevention Cheat Sheet
