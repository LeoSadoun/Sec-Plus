## Official Definition
A set of tools and processes used to ensure that sensitive data is not lost, misused, or accessed by unauthorized users, both inside and outside the network.

## Key Mechanisms/Tools
*   **Data States:**
    *   **Data at Rest:** Data on storage (HDDs, SSDs, tapes). Protect with encryption.
    *   **Data in Motion (Transit):** Data moving over the network. Protect with TLS/VPN.
    *   **Data in Use:** Data currently in RAM or CPU cache. Protect with memory isolation/enclaves.
*   **DLP Types:**
    *   **Endpoint DLP:** Software on workstations that monitors file copies, USB usage, and printing.
    *   **Network DLP:** Monitors outbound email and web traffic for sensitive patterns (e.g., SSNs, Credit Card numbers).
    *   **Cloud DLP:** Scans SaaS environments (OneDrive, Google Drive) for improperly shared files.
*   **Pattern Matching/Regex:** Identifying sensitive data based on its format (e.g., `###-##-####` for SSN).
*   **Watermarking/Tagging:** Applying "Secret" or "Confidential" tags to files that DLP can track.

## Real-World Examples
*   An employee tries to upload a spreadsheet containing 5,000 customer credit card numbers to their personal Dropbox; the Network DLP blocks the upload.
*   A laptop's Endpoint DLP prevents a user from copying a "Project X" folder to an unencrypted USB drive.

## Exam Tips
*   **Keywords:** Data at rest/motion/use, Endpoint vs. Network DLP, Regex, Exfiltration.
*   **Scenario:** Protecting data from being leaked via USB? **Endpoint DLP**.
*   **Scenario:** Identifying sensitive data in an outbound email? **Network DLP**.

## Relationship to other concepts
*   **Enterprise Security:** DLP is a core component of the "Defense in Depth" strategy.
*   **Compliance:** GDPR and PCI DSS require strict DLP controls for personal and financial data.
*   **Incident Response:** DLP alerts often trigger "Data Breach" IR procedures.
