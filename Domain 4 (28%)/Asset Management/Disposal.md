## Official Definition
The secure removal of assets from the organization's inventory, ensuring that all data is unrecoverable and the environment is protected.

## Key Mechanisms/Tools
*   **Data Sanitization:**
    *   **Clearing:** Overwriting data with non-sensitive information (e.g., all zeros).
    *   **Purging:** Using a technical process (like degaussing) to make data recovery impossible even in a lab.
    *   **Destroying:** Physical destruction (shredding, incinerating, crushing).
*   **Degaussing:** Using strong magnets to scramble the data on magnetic media (HDDs, tapes). *Does not work on SSDs.*
*   **Crypto-erasure:** Deleting the encryption keys for a drive, rendering the encrypted data permanently unreadable.
*   **Certificate of Destruction:** Legal documentation provided by a third-party disposal service.

## Real-World Examples
*   A data center uses a commercial shredder to destroy old hard drives before sending them to a recycling facility.
*   Using a software tool to perform a 7-pass overwrite of a server's hard drive before donating the hardware to a charity.

## Exam Tips
*   **Keywords:** Sanitization, clearing/purging/destroying, degaussing (HDD only), crypto-erasure (SSD friendly), certificate of destruction.
*   **Scenario:** Most secure way to dispose of data? Physical destruction.
*   **Scenario:** How to dispose of an SSD? Crypto-erasure or physical shredding (degaussing is ineffective).

## Relationship to other concepts
*   **Data Privacy:** Improper disposal is a major cause of data breaches.
*   **Compliance:** HIPAA and GDPR have strict requirements for the disposal of sensitive data.
*   **Environmental Security:** Assets should be disposed of in an eco-friendly manner after data is secured.
