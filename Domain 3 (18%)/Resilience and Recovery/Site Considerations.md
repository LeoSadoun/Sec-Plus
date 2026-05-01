## Official Definition
Physical and environmental factors related to the selection and setup of a secondary location for disaster recovery and business continuity.

## Key Characteristics/Technical Details
*   **Site Types:**
    *   **Hot Site:** Fully functional duplicate of the production site with real-time data synchronization. Ready in minutes/hours. Most expensive.
    *   **Warm Site:** Has hardware and connectivity but requires data restoration and final configuration. Ready in hours/days.
    *   **Cold Site:** Empty building with power and cooling but no hardware or data. Ready in weeks. Least expensive.
*   **Distance Considerations:** Sites should be far enough apart to avoid the same regional disaster (earthquake, flood) but close enough for data sync latency.
*   **Location Selection:**
    *   Avoid flood plains and high-crime areas.
    *   Proximity to emergency services.
    *   Access to diverse utility providers (power/telecom).

## Real-World Examples
*   **Hot Site:** A financial institution having a second data center 50 miles away that can take over all trading operations instantly if the main center loses power.
*   **Cloud DR:** Using AWS or Azure as a "Hot" or "Warm" site, spinning up resources only when the primary on-premises site fails.

## Exam Tips
*   **Keywords:** Hot/Warm/Cold site, Distance, Geographic diversity, Environmental risks.
*   **Scenario:** An organization needs to be back up in under 1 hour. Which site? Hot Site.
*   **Scenario:** Cost is the most important factor, and downtime of a week is acceptable. Which site? Cold Site.

## Relationship to other concepts
*   **Business Continuity Planning (BCP):** Site selection is a major part of the BCP.
*   **Availability:** Redundant sites ensure long-term availability even in the face of catastrophic physical damage.