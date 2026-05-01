## Official Definition
Ensuring a continuous and clean supply of electricity to critical systems to prevent data loss or hardware damage during outages or fluctuations.

## Key Characteristics/Technical Details
*   **UPS (Uninterruptible Power Supply):** Battery backup that provides immediate power for a short duration (minutes). Protects against surges, sags, and total outages.
*   **Generator:** Provides long-term power (hours/days) during an extended outage. Requires fuel (diesel, natural gas).
*   **Power Distribution Unit (PDU):** A device for distributing power to multiple racks or servers. Smart PDUs can monitor consumption and be toggled remotely.
*   **Redundant Power Supplies:** High-end servers have two power supplies (PSUs) connected to different circuits/PDUs.
*   **Managed Power:** Monitoring power quality and load to prevent overheating or tripping breakers.

## Real-World Examples
*   **UPS:** A rack-mounted APC unit that keeps a server running for 15 minutes—long enough for a generator to start or for the server to shut down gracefully.
*   **Dual-Pole Power:** A server with two power cords, one plugged into "Utility A" and the other into "UPS/Utility B."

## Exam Tips
*   **Keywords:** UPS, Generator, Surge, Sag, Brownout, PDU.
*   **Scenario:** How to prevent a server from crashing during a 5-second power flicker? UPS.
*   **Scenario:** How to keep a data center running during a 3-day city-wide blackout? Generator.
*   **Distinction:** UPS is for short-term/immediate; Generator is for long-term.

## Relationship to other concepts
*   **Availability:** Power is the most basic requirement for availability.
*   **Physical Security:** Generators and fuel tanks must be physically protected from tampering.