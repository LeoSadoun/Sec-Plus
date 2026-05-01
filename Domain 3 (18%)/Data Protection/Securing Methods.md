## Official Definition
Technical and administrative controls used to protect data at rest, in transit, and in use.

## Key Characteristics/Technical Details
*   **Data States:**
    *   **At Rest:** Stored on a disk/drive. Protected by Full Disk Encryption (FDE), AES.
    *   **In Transit:** Moving over a network. Protected by TLS, IPsec, SSH.
    *   **In Use:** Currently being processed in RAM or CPU. Protected by secure enclaves, memory encryption.
*   **Encryption Methods:**
    *   **Symmetric:** Same key for encryption/decryption (AES, 3DES).
    *   **Asymmetric:** Public/Private key pair (RSA, ECC).
*   **Hashing:** Ensures integrity by creating a fixed-length string (MD5, SHA-256).
*   **Digital Signatures:** Provides non-repudiation and integrity (Private key signs, Public key verifies).
*   **Masking/Obfuscation:** Hiding sensitive data by replacing it with dummy characters (e.g., card numbers showing as XXXX-XXXX-XXXX-1234).
*   **Tokenization:** Replacing sensitive data with a non-sensitive "token" (common in PCI).

## Real-World Examples
*   **Data at Rest:** BitLocker or FileVault encrypting a laptop's hard drive.
*   **Data in Transit:** Using HTTPS to access a banking website.
*   **Tokenization:** Apple Pay sending a token instead of the actual credit card number to a merchant.

## Exam Tips
*   **Keywords:** Encryption, Hashing, Tokenization, Masking, FDE, TLS.
*   **Scenario:** How to protect data if a laptop is stolen? Full Disk Encryption (FDE).
*   **Scenario:** How to verify a file hasn't been changed? Hashing (Integrity).
*   **Scenario:** How to prove who sent an email? Digital Signature (Non-repudiation).

## Relationship to other concepts
*   **CIA Triad:** Directly supports **Confidentiality** (Encryption) and **Integrity** (Hashing).
*   **Privacy:** Securing data is a prerequisite for maintaining individual privacy.