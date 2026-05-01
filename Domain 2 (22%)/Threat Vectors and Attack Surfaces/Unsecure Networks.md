## Official Definition
* **Unsecure Network Vector:** A threat vector where an attacker exploits vulnerabilities in network communications or configurations to intercept data, gain unauthorized access, or disrupt services.

## Key Characteristics/Technical Details
* **Open Wi-Fi:** Public hotspots without encryption (e.g., at coffee shops) that allow for easy eavesdropping.
* **Rogue Access Points:** Unauthorized wireless access points installed on a secure network to bypass security controls.
* **Evil Twin:** A malicious access point that mimics a legitimate one (same SSID) to trick users into connecting.
* **Man-in-the-Middle (MitM):** Intercepting and potentially altering communication between two parties without their knowledge.
* **Weak Encryption:** Using outdated protocols like WEP or WPA (original) which can be easily cracked.
* **Wired Sniffing:** Connecting a physical device to an unsecure Ethernet port to capture network traffic.

## Real-World Examples
* **Pineapple WiFi:** A popular tool used by pentesters (and attackers) to easily create rogue access points and conduct MitM attacks.
* **KRACK Attack (2017):** A serious vulnerability in the WPA2 protocol that allowed attackers to decrypt and inject data into protected Wi-Fi traffic.

## Exam Tips
* **Keywords:** Rogue AP, Evil Twin, MitM, Cleartext, Sniffing, Public Wi-Fi, WEP.
* **Scenario:** A user connects to "Airport_Free_WiFi" and finds their credentials stolen; or an attacker "plugs a device into a conference room wall jack."

## Relationship to other concepts
* **Security Controls:** Mitigated by VPNs, WPA3, 802.1X (NAC), and physical security.
* **Malicious Activity:** Often used for Network attacks like ARP poisoning or DNS spoofing.
