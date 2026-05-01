## Official Definition
*   **Authentication:** The process of verifying the identity of a user, device, or system. It is the "Who are you?" phase of the AAA framework.

## Key Mechanisms/Tools
*   **Something you know:** Password, PIN, pattern.
*   **Something you have:** Smart card, hardware token (YubiKey), SMS code, software authenticator (Google Authenticator).
*   **Something you are:** Biometrics (fingerprint, facial recognition, iris scan).
*   **Somewhere you are:** Geolocation, IP address filtering.
*   **Something you do:** Behavioral biometrics (typing rhythm, gait analysis).
*   **Multi-Factor Authentication (MFA):** Combining two or more *different* factors.

## Real-World Examples
*   Logging into a bank account using a **password** (know) and a **one-time password (OTP)** from an app (have).
*   Using **FaceID** on an iPhone to unlock the device.
*   Inserting a **PIV card** (Personal Identity Verification) into a government workstation.

## Exam Tips
*   **Keyword:** "Identify," "Verify," "Factors," "MFA."
*   **Common Trap:** Using two passwords or a password and a PIN is *not* MFA; it is "multi-password" because both are "something you know." MFA requires different categories.
*   **CIA vs. AAA:** Authentication is the first "A" in AAA. It must happen *before* Authorization.

## Relationship to other concepts
*   **vs. Authorization:** Authentication verifies *who* you are; Authorization determines *what* you can do.
*   **Identification:** Identification is claiming an identity (entering a username); Authentication is proving it (entering the password).
