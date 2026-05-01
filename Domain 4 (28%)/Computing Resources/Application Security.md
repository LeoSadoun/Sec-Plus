## Official Definition
The practice of using software, hardware, and procedural methods to protect applications from external threats and vulnerabilities throughout the entire lifecycle.

## Key Mechanisms/Tools
*   **Input Validation:** Ensuring that user-provided data is checked for malicious patterns (prevents SQL Injection, XSS).
*   **Web Application Firewall (WAF):** A specialized firewall that inspects HTTP/HTTPS traffic at Layer 7 to block web-based attacks.
*   **Static Analysis (SAST):** Reviewing the source code for vulnerabilities without running it.
*   **Dynamic Analysis (DAST):** Testing the application while it is running to find vulnerabilities.
*   **Secure Coding Practices:** Following frameworks like **OWASP** (Open Web Application Security Project).
*   **API Security:** Protecting the interfaces that allow applications to communicate (using OAuth, API keys, and rate limiting).

## Real-World Examples
*   Implementing a WAF in front of an e-commerce site to block automated "credential stuffing" attacks.
*   Using parameterized queries in database calls to prevent SQL injection.

## Exam Tips
*   **Keywords:** WAF, Input Validation, SQLi, XSS, SAST vs. DAST, OWASP.
*   **Scenario:** Preventing attacks on web forms? Input validation.
*   **Scenario:** Inspecting Layer 7 traffic for web applications? WAF.

## Relationship to other concepts
*   **Vulnerability Management:** Web application scanning is a specialized part of the vulnerability lifecycle.
*   **Identity and Access Management:** Secure applications must handle session tokens and authentication properly (e.g., using OIDC).
*   **Sandboxing:** New or suspicious applications should be tested in a sandbox before deployment.
