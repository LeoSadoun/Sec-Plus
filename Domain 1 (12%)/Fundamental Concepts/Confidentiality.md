## Official Definition
*   **Confidentiality:** The assurance that information is not disclosed to unauthorized individuals, groups, or processes. It ensures that sensitive data is accessible only to those with a legitimate "need to know."

## Key Mechanisms/Tools
*   **Encryption:** The primary tool for confidentiality (AES for data at rest, TLS for data in transit).
*   **Access Control:** Permissions (ACLs) and physical barriers that restrict data visibility.
*   **Steganography:** Hiding data within other non-secret files (e.g., images or audio).
*   **Obfuscation:** Making data or code difficult to understand without changing its function (e.g., XORing strings).
*   **Data Masking:** Partially hiding data (e.g., showing only the last four digits of a credit card).

## Real-World Examples
*   Using **BitLocker** or **FileVault** to encrypt laptop hard drives.
*   Implementing **HTTPS/TLS** to protect web traffic from eavesdropping.
*   Using **PII (Personally Identifiable Information)** protections in databases to restrict access to HR personnel only.

## Exam Tips
*   **Keyword:** "Privacy," "Eavesdropping," "Snooping," "Encryption."
*   **Scenario:** If a laptop is stolen and the data is unreadable, Confidentiality was maintained via Encryption.
*   **CIA vs. AAA:** Confidentiality is the "C" in the CIA Triad; it focuses on *secrecy*, whereas AAA focuses on *identity and tracking*.

## Relationship to other concepts
*   **vs. Integrity:** Encryption provides confidentiality (hiding data) but does not inherently guarantee the data hasn't been modified (integrity).
*   **Authentication Dependency:** You cannot enforce confidentiality if you cannot first identify (Authenticate) who the user is.
