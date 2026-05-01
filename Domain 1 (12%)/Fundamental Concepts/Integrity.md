## Official Definition
*   **Integrity:** The assurance that data has not been altered or destroyed in an unauthorized manner. It ensures that information remains accurate, complete, and consistent throughout its life cycle.

## Key Mechanisms/Tools
*   **Hashing:** The primary mechanism (MD5, SHA-256). Any change to the data results in a completely different hash value (the "avalanche effect").
*   **Digital Signatures:** Provides integrity and non-repudiation by combining hashing with asymmetric encryption.
*   **Checksums:** Used to detect accidental errors during transmission or storage.
*   **Message Authentication Codes (MAC):** Uses a secret key to verify both data integrity and authenticity.
*   **Version Control:** Tracks changes and allows restoration of previous known-good states.

## Real-World Examples
*   Downloading an ISO file and verifying its **SHA-256 hash** against the vendor's provided hash.
*   A bank server using **Message Authentication Codes** to ensure transaction amounts aren't altered in transit.
*   **File integrity monitoring (FIM)** tools like Tripwire alerting an admin when a system configuration file is modified.

## Exam Tips
*   **Keyword:** "Unauthorized change," "Tampering," "Accuracy," "Hashing."
*   **Scenario:** If an attacker modifies a database record but the hash check fails, Integrity has been protected (or at least the breach was detected).
*   **CIA vs. AAA:** Integrity is the "I" in the CIA Triad; it ensures the *message* is correct, while AAA ensures the *user* is legitimate.

## Relationship to other concepts
*   **vs. Confidentiality:** Hashing provides integrity (detection of changes) but does not provide confidentiality (the data is still readable unless also encrypted).
*   **Non-repudiation:** Digital signatures use integrity mechanisms (hashing) to prevent a sender from denying they sent a message.
