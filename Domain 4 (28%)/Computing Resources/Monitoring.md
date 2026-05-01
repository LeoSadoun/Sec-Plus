## Official Definition
The continuous process of collecting, analyzing, and reporting on the performance, health, and security state of computing resources.

## Key Mechanisms/Tools
*   **Performance Monitor:** Tracking CPU, memory, disk I/O, and network utilization.
*   **System Logs:** Reviewing OS-level events (Event Viewer in Windows, syslog in Linux).
*   **SNMP (Simple Network Management Protocol):** A protocol used to collect information from network devices (routers, switches).
*   **Resource Baselines:** Establishing what "normal" looks like so that anomalies can be detected.
*   **Uptime/Availability Monitoring:** Using "heartbeat" checks to ensure services are reachable.

## Real-World Examples
*   Setting an alert to trigger if a server's CPU usage stays above 95% for more than 10 minutes (possible DoS or crypto-jacking).
*   Using a dashboard to monitor the real-time health of a globally distributed cloud application.

## Exam Tips
*   **Keywords:** Performance, availability, CPU/RAM utilization, SNMP, anomalies.
*   **Scenario:** Identifying a "slow" network? Check resource monitoring for bottlenecks.
*   **Scenario:** Monitoring is about **Availability** (the 'A' in CIA).

## Relationship to other concepts
*   **Alerting and Monitoring:** This is the underlying data collection for the broader alerting infrastructure.
*   **Incident Response:** Monitoring data is often the first indicator of an ongoing incident.
*   **Vulnerability Management:** Monitoring can identify systems that are performing poorly due to unpatched bugs or misconfigurations.
