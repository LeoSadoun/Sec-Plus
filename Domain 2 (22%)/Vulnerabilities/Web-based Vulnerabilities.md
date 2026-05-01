## Official Definition
* **Web-based Vulnerability:** A security flaw in a web application or its underlying server infrastructure that can be exploited via a web browser.

## Key Characteristics/Technical Details
* **SQL Injection (SQLi):** Inserting malicious SQL queries into input fields to manipulate a backend database.
* **Cross-Site Scripting (XSS):**
    * **Stored XSS:** Malicious script is permanently stored on the server (e.g., in a comment field).
    * **Reflected XSS:** Malicious script is "reflected" off a web server (e.g., via a URL parameter).
    * **DOM-based XSS:** The vulnerability exists in client-side code rather than server-side code.
* **Cross-Site Request Forgery (CSRF):** Tricking a logged-in user into submitting a malicious request to a web application.
* **Directory Traversal:** Accessing files and directories outside the web root folder (e.g., `../../etc/passwd`).
* **Insecure Direct Object References (IDOR):** Accessing objects (like user profiles or files) by simply changing an ID in the URL without proper authorization.

## Real-World Examples
* **British Airways Breach (2018):** Attributed to "Magecart," which used a stored XSS-like attack to inject malicious JavaScript into the payment page to steal credit card data.
* **Equifax (2017):** While an application flaw, it was exploited via the web-facing Apache Struts framework.

## Exam Tips
* **Keywords:** SQLi, XSS, CSRF, Directory Traversal, IDOR, WAF, OWASP Top 10.
* **Scenario:** If a user "types code into a login box" or "changes a user ID in the URL to see someone else's data," it's a web-based vulnerability.

## Relationship to other concepts
* **Application Vulnerabilities:** Web-based vulnerabilities are a subset of application vulnerabilities.
* **Mitigation:** Input validation, output encoding, and using a Web Application Firewall (WAF).
