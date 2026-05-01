## Official Definition
The use of simple programs (scripts) to automate repetitive tasks, ensure consistency, and perform complex operations quickly.

## Key Mechanisms/Tools
*   **Common Languages:**
    *   **PowerShell:** Default for Windows environments; powerful access to system internals and AD.
    *   **Python:** Cross-platform; excellent for data analysis, API interaction, and web scraping.
    *   **Bash:** Default for Linux/Unix; ideal for file manipulation and system administration.
*   **Consistency:** Scripts perform the exact same steps every time, eliminating manual "fat-finger" errors.
*   **Speed:** A script can process 1,000 log files in seconds, whereas a human would take hours.
*   **Integration:** Using scripts to connect tools that don't have built-in integrations via their APIs.

## Real-World Examples
*   A PowerShell script that runs every night to identify and disable all AD accounts that haven't logged in for 90 days.
*   A Python script that pulls the daily "Top 10 Malicious IPs" from a threat intelligence feed and adds them to the corporate firewall blocklist.

## Exam Tips
*   **Keywords:** Consistency, speed, repeatability, error reduction, PowerShell/Python/Bash.
*   **Scenario:** Why use a script instead of manual configuration? To ensure **Consistency** and **Repeatability**.
*   **Scenario:** PowerShell is the go-to for **Windows Administration**.

## Relationship to other concepts
*   **Hardening:** Scripts are used to apply hardening settings to hundreds of servers simultaneously.
*   **Vulnerability Management:** Scripts can automate the parsing of scan results and the creation of tickets in Jira/ServiceNow.
*   **Incident Response:** Scripts are used during forensics to quickly gather artifacts (like prefetch files or browser history) from a suspected system.
