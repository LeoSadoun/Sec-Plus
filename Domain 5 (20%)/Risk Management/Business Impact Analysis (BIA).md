## Official Definition
A study that identifies and prioritizes business functions and systems based on their criticality to the organization and the impact of their loss.

## Key Concepts/Technical Details
*   **Criticality:** Ranking functions from "Critical" to "Non-essential."
*   **RTO (Recovery Time Objective):** The maximum targeted duration of time and a service level within which a business process must be restored.
*   **RPO (Recovery Point Objective):** The maximum amount of data loss (measured in time) that is acceptable.
*   **MTD (Maximum Tolerable Downtime):** The total time a business process can be disrupted without causing irreparable harm.
*   **MTBF (Mean Time Between Failures):** Predicted elapsed time between inherent failures of a system during normal operation.
*   **MTTR (Mean Time to Repair):** The average time required to repair a failed component or device.

## Real-World Examples
*   **E-commerce Site:** An RTO of 1 hour and an RPO of 15 minutes (meaning frequent backups and fast recovery are required).
*   **Internal Archiving System:** An RTO of 48 hours and an RPO of 24 hours (less critical).
*   **BIA Survey:** Interviewing department heads to determine which processes are needed for the business to survive.

## Exam Tips
*   **Keywords:** "Criticality," "RTO," "RPO," "MTD," "Downtime," "Impact."
*   **RTO vs. RPO:** RTO is about *time to recover*; RPO is about *data loss*.
*   **Scenario:** If a company can only afford to lose 1 hour of data, they set an **RPO** of 1 hour.

## Relationship to other concepts
*   **Resilience and Recovery (Domain 3):** BIA results dictate the backup strategy and the choice of site types (Hot/Warm/Cold).
*   **Incident Response:** BIA helps prioritize which systems to restore first during a large-scale disaster.
