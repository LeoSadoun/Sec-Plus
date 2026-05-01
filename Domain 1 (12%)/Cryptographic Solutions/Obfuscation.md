## Official Definition
Techniques used to hide the meaning of data, its existence, or its true value to prevent unauthorized access or reverse engineering.

## Key Concepts/Technical Details
*   **Obfuscation:** Making code or data difficult for humans to understand while keeping it functional for machines (e.g., renaming variables in scripts).
*   **Steganography:** Hiding data within another file (the "carrier").
    *   Uses **Least Significant Bit (LSB)** insertion in images or audio.
*   **Tokenization:** Replacing sensitive data with a non-sensitive placeholder (a token).
    *   The mapping is stored in a secure **Vault**.
    *   The token has no mathematical value and cannot be "decrypted."
*   **Data Masking:** Hiding specific parts of data (e.g., `XXXX-XXXX-XXXX-1234`).
    *   **Static Masking:** Applied to data at rest (e.g., in a test database).
    *   **Dynamic Masking:** Applied in real-time as data is viewed.

## Real-World Examples
*   **JavaScript Minification:** Obfuscates code to protect IP and reduce file size.
*   **PCI DSS Compliance:** Using **Tokenization** for credit card numbers so merchants don't store raw card data.
*   **Customer Support Systems:** **Masking** the first 12 digits of a credit card so agents only see the last 4.
*   **Steganography:** Hiding a secret document inside a `.jpg` image of a company logo.

## Exam Tips
*   **Security by Obscurity:** Often associated with obfuscation (not a primary security control, but a layer of defense).
*   **Tokenization vs. Encryption:** Tokenization uses a **vault**; encryption uses an **algorithm/key**.
*   **LSB (Least Significant Bit):** Key technical term for **Steganography**.
*   **Steganography:** Hides the **existence** of the message.

## Relationship to other concepts
*   **Confidentiality:** Helps protect sensitive data via masking and tokenization.
*   **Reverse Engineering:** Obfuscation is used specifically to hinder this.
*   **Data Loss Prevention (DLP):** Steganography is often used by malicious actors to exfiltrate data past DLP systems.
