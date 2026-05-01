## Official Definition
A framework of hardware, software, people, processes, and policies used to create, manage, distribute, use, store, and revoke digital certificates and manage public-key encryption.

## Key Concepts/Technical Details
*   **Certificate Authority (CA):** The trusted third party that issues and signs digital certificates.
*   **Registration Authority (RA):** Verifies the identity of entities requesting certificates before the CA issues them.
*   **Certificate Signing Request (CSR):** A message sent from an applicant to a CA to apply for a digital certificate.
*   **Certificate Revocation List (CRL):** A list of digital certificates that have been revoked by the issuing CA before their scheduled expiration date.
*   **Online Certificate Status Protocol (OCSP):** An internet protocol used for obtaining the revocation status of an X.509 digital certificate in real-time.
*   **OCSP Stapling:** A method for the certificate holder (web server) to query the OCSP responder and "staple" the time-stamped response to the certificate during the TLS handshake.
*   **Public/Private Key Pair:** Asymmetric keys used for encryption and digital signatures.
*   **Trust Models:** Hierarchical (Root CA -> Intermediate CA -> Leaf), Mesh, and Web of Trust.

## Real-World Examples
*   **Web Security (HTTPS):** CAs like DigiCert or Let's Encrypt issue certificates for websites.
*   **Email Encryption:** S/MIME uses PKI to sign and encrypt emails.
*   **Digital Signatures:** Used in PDF documents (Adobe Sign) or software code signing.

## Exam Tips
*   **CA** is the ultimate trust anchor; if it's compromised, everything it signed is suspect.
*   **Root CA** should be kept **offline** for maximum security.
*   **OCSP** is faster and more efficient than **CRL** (which can get very large).
*   **Key Escrow:** Storing a copy of a private key with a third party for recovery purposes.
*   **Stapling** reduces the load on the CA's OCSP responder.

## Relationship to other concepts
*   **Confidentiality:** Enables encryption of data in transit.
*   **Authentication:** Proves the identity of a user or system via certificates.
*   **Non-repudiation:** Provided by digital signatures backed by PKI.
*   **Integrity:** Ensures certificates have not been altered via CA digital signatures.
