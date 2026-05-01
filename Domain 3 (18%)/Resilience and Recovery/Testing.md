## Official Definition
Regularly exercising and validating disaster recovery and business continuity plans to ensure they work as expected when needed.

## Key Characteristics/Technical Details
*   **Test Types:**
    *   **Tabletop Exercise:** Discussion-based session where team members walk through a scenario.
    *   **Walkthrough:** A step-by-step review of the plan and procedures.
    *   **Simulation:** A hands-on test of a specific scenario without impacting production.
    *   **Parallel Test:** Running the recovery systems alongside production to ensure they can handle the load.
    *   **Full Interruption (Cutover):** Shutting down production and running entirely from the recovery site. Most risky.
*   **Frequency:** Tests should be conducted at least annually or after any major infrastructure change.
*   **After-Action Report (AAR):** Documenting what went well and what failed during the test to improve the plan.

## Real-World Examples
*   **Tabletop:** IT leaders sitting in a conference room discussing how they would respond to a ransomware outbreak.
*   **Simulation:** Restoring a backup of the main database to a test server to verify the data is valid and the restoration time is accurate.
*   **Parallel Test:** Turning on the backup mail server to see if it receives mail correctly while the main one is still active.

## Exam Tips
*   **Keywords:** Tabletop, Simulation, Parallel, Full Interruption, Walkthrough, AAR.
*   **Scenario:** Which test is the least disruptive but validates the plan through discussion? Tabletop.
*   **Scenario:** Which test is the most realistic but also the most risky? Full Interruption.

## Relationship to other concepts
*   **Integrity:** Testing ensures the integrity of the recovery process.
*   **Continuous Improvement:** A key part of the "Plan-Do-Check-Act" cycle in security management.