## Official Definition
*   **Non-repudiation:** The assurance that the sender of information is provided with proof of delivery and the recipient is provided with proof of the sender's identity, so neither can later deny having processed the information.

## Key Mechanisms/Tools
*   **Digital Signatures:** The most common tool. It uses the sender's private key to sign a hash of the message; only the sender's public key can verify it.
*   **Digital Certificates:** Issued by a Certificate Authority (CA) to bind a public key to an identity.
*   **Audit Logs:** Detailed records of user actions that can be used as evidence.
*   **Blockchain:** Immutable ledgers that provide a permanent record of transactions.

## Real-World Examples
*   Digitally signing an **e-mail with S/MIME** ensures the recipient knows exactly who sent it and the sender cannot claim their account was "spoofed" (assuming the private key was secure).
*   Using **DocuSign** or similar services for legal contracts to create a cryptographically verifiable record of agreement.
*   **E-commerce transactions** where a merchant receives a signed authorization from a customer's bank.

## Exam Tips
*   **Keyword:** "Cannot deny," "Proof of origin," "Digital Signature," "Private Key."
*   **Scenario:** A user sends an email and later claims they didn't. If the email was digitally signed, the claim is invalidated by Non-repudiation.
*   **CIA vs. AAA:** Non-repudiation is a byproduct of strong **Authentication** and **Integrity**. It is often tested as a specific goal within legal and financial scenarios.

## Relationship to other concepts
*   **Integrity:** Non-repudiation relies on integrity (hashing) to ensure the message wasn't changed, but adds the element of *identity* (via asymmetric encryption).
*   **Asymmetric Encryption:** Non-repudiation is achieved using the **Sender's Private Key**. (Note: Symmetric encryption *cannot* provide non-repudiation because both parties share the same key).
