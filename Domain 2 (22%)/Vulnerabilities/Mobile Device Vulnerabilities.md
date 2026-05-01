## Official Definition
* **Mobile Device Vulnerability:** A security weakness specific to mobile platforms (iOS, Android) and devices (smartphones, tablets) that can be exploited to compromise data or device functionality.

## Key Characteristics/Technical Details
* **Jailbreaking / Rooting:** Removing manufacturer-imposed restrictions on a device, which bypasses security sandboxes and increases the attack surface.
* **Sideloading:** Installing applications from third-party sources rather than official app stores, which bypasses vetting processes.
* **Insecure App Stores:** Malicious apps disguised as legitimate ones in unofficial or poorly regulated app stores.
* **Lack of Updates:** Many Android devices do not receive timely OS patches from manufacturers or carriers.
* **Insecure Wireless:** Vulnerabilities related to Bluetooth, NFC, and Wi-Fi connections.
* **MDM Evasion:** Techniques used to bypass Mobile Device Management (MDM) policies.

## Real-World Examples
* **Pegasus Spyware:** A highly sophisticated "zero-click" exploit used to infect iPhones and Android devices to conduct extensive surveillance.
* **Stagefright (Android):** A series of vulnerabilities in the Android media library that allowed for remote code execution via a specially crafted MMS message.

## Exam Tips
* **Keywords:** Jailbreaking, Rooting, Sideloading, MDM, Sandboxing, SMS/MMS exploits, Remote Wipe.
* **Scenario:** A user "installs an app from a website" instead of the Play Store, or "modifies the OS" to gain full control.

## Relationship to other concepts
* **Mitigation:** MDM/UEM solutions, App wrapping, Containerization, and keeping devices patched.
* **Threat Vectors:** Often targeted via Message-based (Smishing) or Social Engineering.
