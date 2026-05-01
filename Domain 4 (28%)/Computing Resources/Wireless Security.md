## Official Definition
The application of security controls and protocols to protect wireless networks from unauthorized access, data interception, and other wireless-specific threats.

## Key Mechanisms/Tools
*   **WPA3 (Wi-Fi Protected Access 3):** The current standard, using **SAE (Simultaneous Authentication of Equals)** to protect against offline dictionary attacks.
*   **WPA2-Enterprise:** Uses **802.1X** with a RADIUS server for individual user authentication (username/password or certificates).
*   **EAP (Extensible Authentication Protocol):** A framework for wireless authentication (e.g., PEAP, EAP-TLS, EAP-TTLS).
    *   **EAP-TLS:** Requires certificates on both the client and the server (most secure).
*   **Captive Portals:** A web page that users must interact with before being granted network access (common in hotels/airports).
*   **Wireless Site Surveys:** Analyzing heat maps and signal strength to prevent "signal leakage" outside the building.

## Real-World Examples
*   Deploying a corporate Wi-Fi network that requires users to log in with their AD credentials via a RADIUS server (WPA2/WPA3-Enterprise).
*   Installing directional antennas to focus the Wi-Fi signal inside the office and away from the parking lot.

## Exam Tips
*   **Keywords:** WPA3, SAE, 802.1X, RADIUS, EAP-TLS (certificates!), Captive Portal, Rogue AP.
*   **Scenario:** If the question mentions "individual authentication" for Wi-Fi, look for **802.1X** or **Enterprise** mode.
*   **Scenario:** Highest security for Wi-Fi? **WPA3** with **EAP-TLS**.

## Relationship to other concepts
*   **Enterprise Security:** Wireless is an extension of the enterprise network and must be integrated with NAC (Network Access Control).
*   **IAM:** Wireless authentication is a critical entry point for identity management.
*   **Monitoring:** Using WIDS/WIPS (Wireless IDS/IPS) to detect rogue access points or "Evil Twins."
