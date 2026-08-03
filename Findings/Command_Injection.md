# Command Injection

## Severity

Critical

## Description

Command Injection testing assessed whether application inputs could influence operating system command execution.

The testing was performed solely within the WebGoat training environment.

## Assessment Activities

- Input validation review
- Operating system interaction analysis
- HTTP request inspection

## Impact

Command Injection vulnerabilities may allow attackers to:

- Execute operating system commands
- Access sensitive files
- Compromise the host system
- Escalate privileges

## Evidence

Evidence is located within:

- Evidence/Burp/
- Screenshots/

## Recommendations

- Avoid calling operating system commands directly.
- Use safe APIs where possible.
- Validate input using allowlists.
- Execute applications with least privilege.

## References

- OWASP OS Command Injection Defense Cheat Sheet
- CWE-78
