## Official Definition
Integration of hardware and software with network connectivity in order to support critical infrastructure, including power plants, water treatment facilities, and manufacturing lines.

## Key Characteristics/Technical Details
*   **SCADA (Supervisory Control and Data Acquisition):** A system for high-level process supervisory management.
*   **PLC (Programmable Logic Controller):** Industrial computers used for automation of electromechanical processes.
*   **OT (Operational Technology) vs. IT:** ICS focuses on physical safety and process continuity (OT), while traditional IT focuses on data CIA.
*   **Real-Time OS (RTOS):** Operating systems that process data as it comes in, typically without buffering delays.
*   **Legacy Systems:** ICS often use very old hardware/software that cannot be patched or replaced easily.
*   **Safety-First:** In ICS, availability and safety often take precedence over confidentiality.

## Real-World Examples
*   **Smart Grid:** Monitoring and controlling electricity distribution.
*   **Water Treatment:** Automated chemical dosing and flow control.
*   **Manufacturing:** Assembly line robotics controlled by PLCs.
*   **Nuclear Power Plants:** Complex control systems for reactor safety.

## Exam Tips
*   **Keywords:** SCADA, PLC, OT, RTOS, Fieldbus, Modbus.
*   **Scenario:** When discussing critical infrastructure or manufacturing, look for ICS/SCADA.
*   **Critical Risk:** Connecting legacy ICS systems to the public internet without proper isolation (air-gaps or unidirectional gateways).

## Relationship to other concepts
*   **Air-Gapping:** A primary security control for ICS to prevent remote attacks.
*   **Availability:** The most critical component of the CIA triad for ICS.
*   **Physical Controls:** Essential for protecting the sensors and controllers that manage physical processes.