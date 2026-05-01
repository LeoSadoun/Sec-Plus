## Official Definition
The process of converting plaintext into ciphertext using an algorithm and a key to ensure that only authorized parties can read the data.

## Key Concepts/Technical Details
*   **Symmetric Encryption:** Uses a single shared key for both encryption and decryption.
    *   **Algorithms:** AES (Gold Standard), DES (Deprecated), 3DES (Deprecated), Blowfish, Twofish.
    *   **Modes:** Block vs. Stream ciphers.
*   **Asymmetric Encryption:** Uses a public key to encrypt and a private key to decrypt.
    *   **Algorithms:** RSA (Factoring primes), ECC (Elliptic curves), Diffie-Hellman (Key exchange).
*   **Key Exchange:** Methods like Diffie-Hellman (DH) used to securely share symmetric keys over an insecure channel.
*   **Perfect Forward Secrecy (PFS):** Ensures that a compromise of long-term keys does not compromise past session keys (achieved via DHE or ECDHE).
*   **Quantum Resistance:** Algorithms designed to be secure against attacks by quantum computers.

## Real-World Examples
*   **AES-256:** Used for Full Disk Encryption (BitLocker, FileVault) and securing government data.
*   **TLS (SSL):** Uses asymmetric encryption for the handshake and symmetric encryption for bulk data transfer.
*   **ECC:** Preferred for mobile devices and IoT due to high security with smaller key sizes.

## Exam Tips
*   **Symmetric = Fast:** Use for bulk data (data at rest).
*   **Asymmetric = Secure Key Exchange:** Use to solve the "key distribution problem."
*   **ECC > RSA:** Provides same security with smaller keys; better for low-power devices.
*   **PFS:** Look for "Ephemeral" (DHE/ECDHE) to ensure future session security.
*   **Confidentiality:** The primary goal of encryption.

## Relationship to other concepts
*   **Confidentiality:** Direct implementation of the "C" in CIA.
*   **Non-repudiation:** Provided by asymmetric encryption when used for digital signatures.
*   **PKI:** Provides the framework for managing the keys used in asymmetric encryption.
