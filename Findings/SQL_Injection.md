# SQL Injection

## Severity

High

## Description

The assessment included testing for SQL Injection vulnerabilities within the WebGoat training environment. SQL Injection occurs when user input is improperly handled by backend database queries.

## Assessment Activities

- Input validation review
- SQL Injection lesson assessment
- Request analysis using Burp Suite
- Verification using SQLMap where appropriate

## Impact

Successful SQL Injection may result in:

- Unauthorized data disclosure
- Database modification
- Authentication bypass
- Loss of confidentiality and integrity

## Evidence

Supporting evidence is available within:

- Evidence/Burp/
- Evidence/SQLMap/
- Screenshots/

## Recommendations

- Use parameterized queries.
- Implement prepared statements.
- Validate and sanitize user input.
- Apply least-privilege database permissions.

## References

- OWASP SQL Injection Prevention Cheat Sheet
- CWE-89
