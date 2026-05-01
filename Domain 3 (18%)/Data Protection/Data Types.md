## Official Definition
Categories of data based on its source, use, and the level of protection it requires according to regulatory and organizational standards.

## Key Characteristics/Technical Details
*   **PII (Personally Identifiable Information):** Data that can uniquely identify an individual (Name, SSN, biometric records).
*   **PHI (Protected Health Information):** Health status, provision of health care, or payment for health care (Medical records, health insurance info).
*   **PCI-DSS (Payment Card Industry Data Security Standard):** Requirements for organizations that handle branded credit cards.
*   **Public vs. Private Data:**
    *   **Public:** No risk if disclosed (Marketing materials).
    *   **Private/Internal:** Risk to company if disclosed (Internal memos).
    *   **Confidential/Secret:** High risk; contains trade secrets or intellectual property.
*   **Regulated Data:** Data subject to laws like GDPR (EU), CCPA (California), or HIPAA (Healthcare).

## Real-World Examples
*   **PII:** A customer's full name combined with their home address and date of birth.
*   **PHI:** A doctor's note about a patient's diagnosis stored in an electronic health record (EHR).
*   **PCI:** Credit card numbers and CVV codes processed by an e-commerce website.

## Exam Tips
*   **Keywords:** PII, PHI, PCI, GDPR, Sensitive, Public.
*   **Scenario:** If data can identify a person, it's PII.
*   **Scenario:** If data is about a medical condition, it's PHI.
*   **Distinction:** Know that HIPAA protects PHI, while GDPR protects "Personal Data" of EU citizens.

## Relationship to other concepts
*   **Confidentiality:** The primary goal of identifying data types is to apply the appropriate level of confidentiality controls.
*   **DLP (Data Loss Prevention):** DLP tools are configured to recognize specific data types (like SSN formats) to prevent unauthorized export.