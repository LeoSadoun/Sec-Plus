## Official Definition
* **Application Attack:** An attack that targets the logic, data, or communication of a software application.

## Key Characteristics/Technical Details
* **Injection Attacks:** SQLi, Command Injection, XML Injection (XXE).
* **Buffer Overflow:** Overwriting memory buffers to crash an application or execute arbitrary code.
* **Replay Attack:** Intercepting a valid communication and later re-sending it to impersonate a user or perform an unauthorized action.
* **Session Hijacking:** Stealing a user's session ID (often via XSS or sniffing) to take over their active session.
* **API Attacks:** Exploiting vulnerabilities in application programming interfaces to steal data or bypass security.
* **Directory Traversal:** Accessing restricted files by manipulating file paths.

## Real-World Examples
* **Equifax (2017):** A classic application attack exploiting a vulnerability in a web framework.
* **Heartbleed:** An attack targeting the implementation of a specific protocol (TLS) within an application library.

## Exam Tips
* **Keywords:** SQLi, Buffer overflow, Replay, Session hijacking, Injection, API.
* **Scenario:** An attacker "inserts code into a web form" or "captures and resends a login token."

## Relationship to other concepts
* **Vulnerabilities:** Exploits Application and Web-based vulnerabilities.
* **Mitigation:** WAF, input validation, and secure session management.
