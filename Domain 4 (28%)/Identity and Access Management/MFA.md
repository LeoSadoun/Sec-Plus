## Official Definition
An authentication method in which a user is granted access only after successfully presenting two or more pieces of evidence (or factors) to an authentication mechanism.

## Key Mechanisms/Tools
*   **Authentication Factors:**
    *   **Something You Know:** Password, PIN, security questions.
    *   **Something You Have:** Smart card, hardware token (YubiKey), smartphone (OTP app).
    *   **Something You Are:** Biometrics (Fingerprint, FaceID, Retina scan).
    *   **Somewhere You Are:** Geolocation, IP address.
    *   **Something You Do:** Handwriting analysis, typing cadence.
*   **TOTP (Time-based One-Time Password):** Codes that change every 30-60 seconds (e.g., Google Authenticator).
*   **HOTP (HMAC-based One-Time Password):** Codes that change based on a counter rather than time.
*   **Push Notifications:** Approving a login request via a mobile app notification.

## Real-World Examples
*   Entering your password and then tapping a notification on your phone to log into your bank account.
*   Requiring a YubiKey (Something You Have) plus a PIN (Something You Know) to access a secure server room.

## Exam Tips
*   **Keywords:** Multi-factor, factors (Know/Have/Are/Where/Do), TOTP, Biometrics.
*   **Scenario:** Using a password and a PIN is **NOT** MFA (both are "Something You Know").
*   **Scenario:** Most secure MFA? Hardware tokens or Out-of-band (Push) notifications.

## Relationship to other concepts
*   **SSO:** MFA is a critical security layer for SSO implementations.
*   **Privileged Access Tools:** MFA should be mandatory for all administrative/privileged access.
*   **Mobile Solutions:** Smartphones are the most common "Something You Have" factor in modern MFA.
