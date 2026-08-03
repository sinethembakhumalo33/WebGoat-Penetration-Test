# Authentication Testing

## Severity

Medium

## Description

Authentication mechanisms were assessed to evaluate the application's ability to securely identify users and protect against unauthorized access. The assessment included reviewing login functionality, account registration, password policies, user enumeration, and error handling.

## Assessment Activities

- Login functionality review
- Account registration testing
- Password policy evaluation
- Authentication error message analysis
- Session creation verification

## Impact

Weak authentication controls can increase the risk of:

- Unauthorized account access
- Credential guessing attacks
- User enumeration
- Account compromise

## Evidence

See the `Evidence/Burp/` and `Screenshots/` directories for HTTP requests, responses, and authentication workflow captures.

## Recommendations

- Enforce strong password requirements.
- Implement account lockout or rate limiting.
- Avoid revealing whether usernames exist.
- Enable multi-factor authentication where appropriate.
- Log authentication events for monitoring.

## References

- OWASP Authentication Cheat Sheet
- OWASP Web Security Testing Guide (WSTG)
