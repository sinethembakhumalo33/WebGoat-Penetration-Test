# Session Management

## Severity

Medium

## Description

Session management controls were reviewed to determine whether authenticated sessions were securely maintained throughout user interactions.

The assessment focused on session cookie configuration, logout behavior, session expiration, and token handling.

## Assessment Activities

- Cookie analysis
- Logout validation
- Session reuse testing
- Session timeout review

## Impact

Weak session management may allow attackers to:

- Hijack authenticated sessions
- Reuse stolen session tokens
- Access protected resources after logout

## Evidence

Relevant HTTP requests and cookie information are stored in the `Evidence/Burp/` directory.

## Recommendations

- Configure cookies with HttpOnly.
- Enable the Secure flag.
- Use SameSite protections.
- Invalidate sessions after logout.
- Implement appropriate session expiration.

## References

- OWASP Session Management Cheat Sheet
- OWASP WSTG
