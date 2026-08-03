# Cross-Site Scripting (XSS)

## Severity

High

## Description

Cross-Site Scripting testing was performed to identify locations where untrusted input could be interpreted by a user's browser.

The assessment considered reflected, stored, and DOM-based XSS scenarios within the WebGoat application.

## Assessment Activities

- Input validation review
- Client-side rendering analysis
- Browser behavior observation
- HTTP response inspection

## Impact

Successful XSS attacks may allow attackers to:

- Execute malicious JavaScript
- Steal session information
- Modify page content
- Perform actions on behalf of authenticated users

## Evidence

Evidence is stored within:

- Screenshots/
- Evidence/Burp/

## Recommendations

- Encode output appropriately.
- Validate user input.
- Implement Content Security Policy (CSP).
- Avoid unsafe DOM manipulation.

## References

- OWASP Cross Site Scripting Prevention Cheat Sheet
- CWE-79
