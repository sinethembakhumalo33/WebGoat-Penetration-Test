# OWASP Web Security Testing Guide (WSTG) Methodology

## Overview

This penetration test follows the methodology outlined in the OWASP Web Security Testing Guide (WSTG), a widely recognized framework for assessing the security of web applications.

The objective of this assessment is to identify security weaknesses within the OWASP WebGoat application in a controlled laboratory environment while documenting findings using professional penetration testing practices.

---

## Assessment Phases

### 1. Information Gathering

- Identify the target application
- Collect HTTP headers
- Perform banner grabbing
- Identify exposed services

---

### 2. Reconnaissance

- Map the application
- Identify pages and endpoints
- Review robots.txt and sitemap.xml
- Analyze JavaScript files

---

### 3. Authentication Testing

- Review login functionality
- Evaluate password policy
- Test account registration
- Review authentication error messages

---

### 4. Session Management

- Inspect session cookies
- Review cookie security attributes
- Validate logout functionality
- Assess session expiration

---

### 5. Input Validation

Assess common input validation vulnerabilities, including:

- SQL Injection
- Cross-Site Scripting (XSS)
- Command Injection

---

### 6. Authorization Testing

Evaluate access control mechanisms, including:

- Insecure Direct Object References (IDOR)
- Broken Access Control

---

### 7. Security Configuration Review

Review application security configuration, including:

- HTTP security headers
- Cookie configuration
- Server information disclosure

---

### 8. Reporting

For each finding, document:

- Description
- Risk Rating
- CVSS Score
- Evidence
- Impact
- Remediation Recommendations
- References

---

## References

- OWASP Web Security Testing Guide (WSTG)
- OWASP Top 10
- OWASP Cheat Sheet Series
