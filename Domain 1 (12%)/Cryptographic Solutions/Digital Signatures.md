## Official Definition
A cryptographic process used to verify the authenticity, integrity, and non-repudiation of a digital message, document, or software.

## Key Concepts/Technical Details
*   **Process:**
    1.  Sender creates a **Hash** of the message.
    2.  Sender encrypts the hash with their **Private Key** (this is the signature).
    3.  Receiver decrypts the signature with the sender's **Public Key** to get the hash.
    4.  Receiver hashes the message themselves and compares the two hashes.
*   **Authentication:** Proves who sent the message (only the sender has their private key).
*   **Integrity:** Proves the message wasn't altered (if it changed, the hashes won't match).
*   **Non-repudiation:** The sender cannot deny sending the message because only their private key could have created the signature.
*   **Algorithms:** RSA, DSA, ECDSA (Elliptic Curve Digital Signature Algorithm).

## Real-World Examples
*   **Code Signing:** Developers sign software (e.g., `.exe` or `.app` files) to prove it hasn't been modified by malware.
*   **S/MIME:** Used to digitally sign and encrypt emails.
*   **PDF Documents:** Adobe Acrobat uses digital signatures for legally binding contracts.

## Exam Tips
*   **Non-repudiation:** This is the most common "look-for" term for digital signatures.
*   **Private Key signs, Public Key verifies:** Never confuse these two.
*   **Integrity + Authentication:** Digital signatures provide both.
*   **Lookup:** If the question mentions "proving the sender's identity and that the file wasn't changed," the answer is Digital Signature.

## Relationship to other concepts
*   **Asymmetric Encryption:** The underlying technology that makes digital signatures possible.
*   **Hashing:** Used to create the message digest that is actually signed.
*   **PKI:** Provides the certificates that bind a public key to a specific identity.
