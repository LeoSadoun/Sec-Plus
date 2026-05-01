## Official Definition
The management of changes to documents, computer programs, and other collections of information to ensure integrity and provide a path for recovery.

## Key Concepts/Technical Details
*   **Repository:** The central location where all versions of a file are stored.
*   **Commit/Check-in:** The process of saving a new version of a file to the repository with a descriptive message.
*   **Branching:** Creating a separate path of development (e.g., for a new feature) without affecting the main code.
*   **Merging:** Combining changes from different branches back into the main (trunk/master) branch.
*   **Reversion (Rollback):** The ability to quickly return a file or system to a previous known-good version.
*   **Tags/Releases:** Marking specific points in history as important (e.g., "Version 1.0").

## Real-World Examples
*   **Git:** The industry-standard version control system (used with GitHub, GitLab).
*   **Subversion (SVN):** An older, centralized version control system.
*   **Infrastructure as Code (IaC):** Using Git to manage Terraform or Ansible scripts, ensuring that infrastructure changes are tracked like software.

## Exam Tips
*   **Integrity:** Version control ensures that you know exactly what changed and who changed it.
*   **Accountability:** Every commit is tied to a user identity.
*   **Recovery:** The "Look-for" term is the ability to **roll back** to a previous version if a new update introduces a bug or vulnerability.

## Relationship to other concepts
*   **DevSecOps:** Integrating security testing directly into the version control and CI/CD pipeline.
*   **Change Management:** Version control provides the technical "truth" of what was actually changed.
*   **Software Development Life Cycle (SDLC):** A core component of modern software development.
