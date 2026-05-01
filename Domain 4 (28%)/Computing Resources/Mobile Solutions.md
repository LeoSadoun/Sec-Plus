## Official Definition
The implementation of security controls, policies, and technologies to protect portable devices (smartphones, tablets, laptops) and the data they access or store.

## Key Mechanisms/Tools
*   **MDM (Mobile Device Management):** Centralized tool to enforce passcodes, remote wipe, and push updates.
*   **MAM (Mobile Application Management):** Controlling security at the app level rather than the device level (e.g., preventing copy/paste from corporate email to personal apps).
*   **Deployment Models:** 
    *   **BYOD (Bring Your Own Device):** User-owned; highest risk, privacy concerns.
    *   **COPE (Corporate Owned, Personally Enabled):** Company-owned, but users can use it for personal tasks.
    *   **CYOD (Choose Your Own Device):** Users pick from a pre-approved list of company-owned devices.
*   **Containerization:** Isolating work data from personal data on a single device.
*   **Geofencing:** Restricting device features based on physical location (e.g., disabling the camera while inside a secure facility).

## Real-World Examples
*   An employee loses their phone; the IT department uses an MDM to perform a **Remote Wipe** of only corporate data (selective wipe).
*   Using **Micro-segmentation** or a **Client-to-Site VPN** to ensure mobile devices can only access specific internal resources.

## Exam Tips
*   **Keywords:** Remote wipe, geofencing, containerization, MDM vs. MAM, BYOD/COPE.
*   **Scenario:** Privacy is the main concern in BYOD; use MAM or containerization to separate data.
*   **Scenario:** A device enters a "no-photo zone" and the camera is automatically disabled? Geofencing.

## Relationship to other concepts
*   **IAM:** Mobile devices often require MFA or certificate-based authentication to access corporate networks.
*   **Asset Management:** Every mobile device must be tracked as a corporate asset or a registered BYOD device.
*   **DLP:** Mobile security prevents data leakage through unencrypted storage or unauthorized cloud backups.
