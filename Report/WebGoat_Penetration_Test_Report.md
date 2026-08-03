# WebGoat Penetration Test Report

**Project:** WebGoat Penetration Testing Assessment

**Assessor:** Sinethemba Khumalo

**Date:** August 2026

**Target Application:** OWASP WebGoat

**Environment:** Personal Laboratory

---

# Executive Summary

A security assessment was conducted against OWASP WebGoat, an intentionally vulnerable web application used for cybersecurity training. The objective was to demonstrate a structured web application penetration testing methodology using industry-standard tools while documenting findings and remediation recommendations.

The assessment focused on common web application security risks aligned with the OWASP Web Security Testing Guide (WSTG). Testing included reconnaissance, authentication, session management, input validation, access control, and injection-related vulnerabilities.

---

# Scope

## In Scope

- OWASP WebGoat
- HTTP services
- Authentication mechanisms
- Session management
- Input validation
- Authorization controls
- API endpoints
- Client-side functionality

## Out of Scope

- Host operating system
- Network infrastructure
- Denial-of-Service testing
- Third-party services

---

# Rules of Engagement

Testing was conducted exclusively within a personal lab environment using OWASP WebGoat. No third-party systems or production environments were assessed.

---

# Methodology

The assessment followed the OWASP Web Security Testing Guide (WSTG).

Testing phases included:

- Information Gathering
- Reconnaissance
- Authentication Testing
- Session Management
- SQL Injection
- Cross-Site Scripting (XSS)
- Cross-Site Request Forgery (CSRF)
- Access Control Testing (IDOR)
- Command Injection
- Reporting

---

# Tools Used

| Tool | Purpose |
|------|---------|
| Burp Suite | HTTP interception and manipulation |
| Nmap | Service enumeration |
| Gobuster | Directory enumeration |
| ffuf | Content discovery |
| Nikto | Web server assessment |
| SQLMap | SQL injection verification |
| curl | HTTP requests |
| Firefox | Browser testing |

---

# Attack Surface Overview

The application exposed multiple HTTP endpoints for authentication, lesson content, and user interaction. Dynamic content and API endpoints were mapped through browser analysis, Burp Suite, and directory enumeration.

---

# Findings Summary

| Finding | Severity |
|----------|----------|
| Authentication Testing | Informational |
| Session Management Review | Medium |
| SQL Injection Lesson | High |
| Cross-Site Scripting (XSS) Lesson | High |
| Cross-Site Request Forgery (CSRF) Lesson | Medium |
| Insecure Direct Object Reference (IDOR) Lesson | High |
| Command Injection Lesson | Critical |

---

# Detailed Findings

Refer to the documentation in the **Findings/** directory for:

- Authentication
- Session Management
- SQL Injection
- XSS
- CSRF
- IDOR
- Command Injection

---

# Risk Ratings

Risk ratings are based on the Common Vulnerability Scoring System (CVSS) and the potential impact demonstrated within the WebGoat training environment.

---

# Evidence

Supporting evidence is available in:

- Screenshots/
- Evidence/Burp/
- Evidence/Nmap/
- Evidence/Gobuster/
- Evidence/Nikto/
- Evidence/SQLMap/
- Evidence/ffuf/

---

# Recommendations

General recommendations include:

- Validate all user input.
- Use parameterized SQL queries.
- Implement server-side input validation.
- Apply output encoding to prevent XSS.
- Enforce CSRF protection.
- Apply least privilege.
- Implement secure session management.
- Validate authorization on every request.
- Sanitize system command input.
- Keep software updated.

---

# Conclusion

The assessment demonstrated a structured penetration testing workflow aligned with the OWASP WSTG. While WebGoat is intentionally vulnerable for educational purposes, the testing process mirrors professional web application security assessments, including reconnaissance, exploitation, evidence collection, risk assessment, and remediation guidance.

---

# Appendix

Additional evidence and raw outputs are available within the repository:

- Report/
- Findings/
- Evidence/
- Screenshots/
- Methodology/
