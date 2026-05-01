## Official Definition
* **Application Vulnerability:** A weakness or flaw in the design, implementation, or operation of a software application that could be exploited to violate the organization's security policy.

## Key Characteristics/Technical Details
* **Injection Flaws:** SQL Injection (SQLi), Command Injection, and LDAP Injection where malicious input is executed by the application.
* **Broken Access Control:** Improperly enforced restrictions on what authenticated users are allowed to do.
* **Cross-Site Scripting (XSS):** Injecting malicious scripts into web pages viewed by other users.
* **Cross-Site Request Forgery (CSRF):** Forcing a user to execute unwanted actions on a web application in which they are currently authenticated.
* **Insecure Deserialization:** Flaws that allow an attacker to remotely execute code or tamper with application logic by sending malicious serialized objects.
* **Improper Input Validation:** The root cause of many application vulnerabilities; failing to properly sanitize user-provided data.

## Real-World Examples
* **Heartbleed (2014):** A critical vulnerability in the OpenSSL library that allowed attackers to read memory from a server, potentially exposing private keys and user data.
* **Log4Shell (2021):** A critical vulnerability in the Log4j logging library that allowed for easy remote code execution (RCE) via simple log messages.

## Exam Tips
* **Keywords:** Injection, XSS, CSRF, Input validation, SDLC, Buffer overflow.
* **Scenario:** If a question mentions "unsanitized input" leading to "unauthorized data access," it's an application vulnerability.

## Relationship to other concepts
* **Malicious Activity:** Targeted by Application Attacks.
* **Mitigation:** Secure coding practices, Web Application Firewalls (WAF), and Static/Dynamic Application Security Testing (SAST/DAST).
