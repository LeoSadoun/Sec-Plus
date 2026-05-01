## Official Definition
A one-way cryptographic function that maps data of arbitrary size to a fixed-size bit string (a hash).

## Key Concepts/Technical Details
*   **One-Way Function:** It is computationally infeasible to reverse the process (plaintext cannot be recovered from the hash).
*   **Deterministic:** The same input always produces the exact same hash.
*   **Collision Resistance:** It should be extremely difficult to find two different inputs that produce the same hash.
*   **Fixed Length:** Regardless of input size (1 KB or 1 TB), the output hash length is always the same (e.g., 256 bits for SHA-256).
*   **Salting:** Adding random data (a salt) to a password before hashing to prevent rainbow table attacks.
*   **Key Stretching:** Running a hash function multiple times (e.g., PBKDF2, bcrypt) to slow down brute-force attacks.
*   **Algorithms:**
    *   **MD5:** 128-bit; deprecated due to collision vulnerabilities.
    *   **SHA-1:** 160-bit; deprecated.
    *   **SHA-2:** (SHA-256, SHA-512) Current standard.
    *   **SHA-3:** Newest standard; uses a different internal structure (sponge construction).
    *   **HMAC:** Hash-based Message Authentication Code; uses a secret key combined with a hash for integrity and authentication.

## Real-World Examples
*   **Password Storage:** Storing hashes in a database instead of plaintext.
*   **File Integrity:** Using MD5 or SHA-256 checksums to verify that a downloaded file hasn't been tampered with.
*   **Digital Signatures:** The message is hashed before being encrypted with a private key.

## Exam Tips
*   **Keywords:** "Fixed-length", "One-way", "Integrity".
*   **Collision:** When two different inputs produce the same hash.
*   **Salt:** Primary defense against **Rainbow Tables**.
*   **HMAC:** Provides both **Integrity** and **Authentication**.

## Relationship to other concepts
*   **Integrity:** The primary goal of hashing (the "I" in CIA).
*   **Digital Signatures:** Relies on hashing to ensure the message content hasn't changed.
*   **Blockchain:** Uses hashing to link blocks together in an immutable chain.
